# jenkins_cicd_script
Jenkins CI/CD example script

<mxfile host="app.diagrams.net" modified="2023-07-21T15:59:46.311Z" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36" etag="iTo4mG7YqPJXfnlowrkM" version="21.6.5" type="github">
  <diagram name="페이지-1" id="3S672CWo83TiiCjc-UTG">
    <mxGraphModel dx="1434" dy="764" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" background="none" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="d_0SFwmgrerE2drZfnpr-12" value="" style="rounded=0;whiteSpace=wrap;html=1;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=20;" vertex="1" parent="1">
          <mxGeometry x="40" y="240" width="760" height="260" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-9" value="" style="group" vertex="1" connectable="0" parent="1">
          <mxGeometry x="560" y="270" width="160" height="176.76999999999998" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-10" value="" style="shape=umlFrame;whiteSpace=wrap;html=1;pointerEvents=0;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=20;movable=1;resizable=1;rotatable=1;deletable=1;editable=1;locked=0;connectable=1;width=50;height=30;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-9">
          <mxGeometry x="20" y="36.76999999999998" width="140" height="140" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-11" value="" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://subicura.com/generated/assets/article_images/2017-01-19-docker-guide-for-beginners-1/docker-logo-800-b3c79c1cb.png;movable=1;resizable=1;rotatable=1;deletable=1;editable=1;locked=0;connectable=1;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-9">
          <mxGeometry width="78.8" height="70.32" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-31" value="&lt;font color=&quot;#0000ff&quot; style=&quot;font-size: 16px;&quot;&gt;172.17.0.4&lt;/font&gt;" style="text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontSize=20;fontFamily=Architects Daughter;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-9">
          <mxGeometry x="60" y="146.76999999999998" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-13" value="" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://storage.googleapis.com/static.fastcampus.co.kr/prod/uploads/202206/085227-704/froala-uploads-1653627056791-%EC%88%98%EC%A0%95%EB%90%A8-vertical-logo-monochromatic.png;" vertex="1" parent="1">
          <mxGeometry x="10" y="193.21" width="89.73" height="76.79" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-14" value="" style="rounded=0;whiteSpace=wrap;html=1;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=20;fillColor=#174c97;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="10" y="525" width="810" height="15" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-23" value="172.17.0.3" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://img1.daumcdn.net/thumb/R1280x0/?fname=http://t1.daumcdn.net/brunch/service/user/797z/image/4r7u74bLHPXOZsr0x17pikAwrMI.png;clipPath=inset(2.31% 12% 4.62% 15.67% round 33%);fontColor=#0000FF;fontSize=16;spacing=-4;" vertex="1" parent="1">
          <mxGeometry x="340.22" y="320" width="119.78" height="100.18" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-5" value="" style="group" vertex="1" connectable="0" parent="1">
          <mxGeometry x="80" y="270" width="1219.73" height="970" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-20" value="" style="group" vertex="1" connectable="0" parent="d_0SFwmgrerE2drZfnpr-5">
          <mxGeometry width="710" height="458.5" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-42" value="kubectl apply -f" style="edgeStyle=orthogonalEdgeStyle;rounded=0;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=1;entryDx=0;entryDy=0;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=16;strokeColor=#FF0000;exitX=0.5;exitY=0.993;exitDx=0;exitDy=0;exitPerimeter=0;fontStyle=1;spacingRight=-50;" edge="1" parent="d_0SFwmgrerE2drZfnpr-20" source="d_0SFwmgrerE2drZfnpr-2" target="d_0SFwmgrerE2drZfnpr-39">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="90" y="430" />
              <mxPoint x="415" y="430" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-2" value="" style="shape=umlFrame;whiteSpace=wrap;html=1;pointerEvents=0;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=20;movable=1;resizable=1;rotatable=1;deletable=1;editable=1;locked=0;connectable=1;width=50;height=30;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="20" y="39.99999999999998" width="140" height="140" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-4" value="" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://subicura.com/generated/assets/article_images/2017-01-19-docker-guide-for-beginners-1/docker-logo-800-b3c79c1cb.png;movable=1;resizable=1;rotatable=1;deletable=1;editable=1;locked=0;connectable=1;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry width="78.8" height="70.32" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-21" value="172.17.0.2" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://crispyblog.kr:5000/static/img/postImg/da5a8caf-6ccc-4aa2-b8d1-d673a3f0a4e6_jenkins.png;fontColor=#0000FF;fontSize=16;spacing=-15;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="28.380000000000003" y="36.77000000000001" width="123.23" height="123.23" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-41" value="&lt;b&gt;&lt;font color=&quot;#000000&quot;&gt;ansible-playbook -i {hosts file path} {playbook file path}&lt;/font&gt;&lt;/b&gt;" style="edgeStyle=orthogonalEdgeStyle;rounded=0;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;orthogonalLoop=1;jettySize=auto;html=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=16;fontColor=#FF0000;strokeColor=#FF0000;spacingRight=-100;spacingTop=-50;" edge="1" parent="d_0SFwmgrerE2drZfnpr-20" source="d_0SFwmgrerE2drZfnpr-7" target="d_0SFwmgrerE2drZfnpr-39">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-7" value="" style="shape=umlFrame;whiteSpace=wrap;html=1;pointerEvents=0;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=20;movable=1;resizable=1;rotatable=1;deletable=1;editable=1;locked=0;connectable=1;width=50;height=30;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="250" y="40.00000000000001" width="140" height="140" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-25" value="" style="rounded=0;whiteSpace=wrap;html=1;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=20;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="520" y="70" width="100" height="80" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-24" value="" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://subicura.com/generated/assets/article_images/2017-01-19-docker-guide-for-beginners-1/docker-logo-800-b3c79c1cb.png;movable=1;resizable=1;rotatable=1;deletable=1;editable=1;locked=0;connectable=1;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="530" y="71.61000000000001" width="78.8" height="70.32" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-36" value="&lt;font style=&quot;font-size: 17px;&quot;&gt;&lt;b&gt;ssh&lt;/b&gt;&lt;/font&gt;" style="edgeStyle=orthogonalEdgeStyle;rounded=0;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;orthogonalLoop=1;jettySize=auto;html=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=16;entryX=0.021;entryY=0.487;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="d_0SFwmgrerE2drZfnpr-20" source="d_0SFwmgrerE2drZfnpr-2" target="d_0SFwmgrerE2drZfnpr-7">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="205" y="107" />
              <mxPoint x="205" y="108" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-37" value="&lt;font color=&quot;#00ff00&quot; style=&quot;font-size: 14px;&quot;&gt;&lt;b&gt;playbook.yml&lt;/b&gt;&lt;/font&gt;" style="shape=note;size=20;whiteSpace=wrap;html=1;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=20;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="350" y="-10" width="60" height="70" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-38" value="&lt;font color=&quot;#00ff00&quot; style=&quot;font-size: 14px;&quot;&gt;&lt;b&gt;k8s script.yml&lt;/b&gt;&lt;/font&gt;" style="shape=note;size=20;whiteSpace=wrap;html=1;sketch=1;hachureGap=4;jiggle=2;curveFitting=1;fontFamily=Architects Daughter;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DArchitects%2BDaughter;fontSize=20;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="480" y="315" width="60" height="70" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-17" value="ubuntu" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/Logo-ubuntu_cof-orange-hex.svg/1200px-Logo-ubuntu_cof-orange-hex.svg.png;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="285" y="312.5" width="65" height="65" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-39" value="" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://www.syncfusion.com/books/using-netcore-docker-and-kubernetes-succinctly/Images/kubernetes-cluster-components.png;clipPath=inset(22.25% 67.67% 44.24% 5%);" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="370" y="312.5" width="89.69" height="70" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-40" value="windows" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://blogs.windows.com/wp-content/uploads/prod/2020/08/windows-logo-social.png;spacing=-3;" vertex="1" parent="d_0SFwmgrerE2drZfnpr-20">
          <mxGeometry x="151.61" y="312.5" width="131.43" height="69" as="geometry" />
        </mxCell>
        <mxCell id="d_0SFwmgrerE2drZfnpr-8" value="" style="shape=image;verticalLabelPosition=bottom;labelBackgroundColor=default;verticalAlign=top;aspect=fixed;imageAspect=0;image=https://subicura.com/generated/assets/article_images/2017-01-19-docker-guide-for-beginners-1/docker-logo-800-b3c79c1cb.png;movable=1;resizable=1;rotatable=1;deletable=1;editable=1;locked=0;connectable=1;" vertex="1" parent="1">
          <mxGeometry x="310" y="270" width="78.8" height="70.32" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
