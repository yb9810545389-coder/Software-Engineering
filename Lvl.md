<mxfile host="app.diagrams.net">
  <diagram name="Level 1 DFD - Balanced">
    <mxGraphModel dx="1300" dy="900" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1300" pageHeight="900">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>

        <!-- External Entities -->
        <mxCell id="2" value="Patient" style="rounded=0;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="50" y="250" width="140" height="70" as="geometry"/>
        </mxCell>

        <mxCell id="3" value="Front Desk Officer" style="rounded=0;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="50" y="450" width="180" height="70" as="geometry"/>
        </mxCell>

        <mxCell id="4" value="Doctor" style="rounded=0;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="1050" y="300" width="140" height="70" as="geometry"/>
        </mxCell>

        <!-- Processes -->
        <mxCell id="5" value="1.0 Register Patient" style="ellipse;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="350" y="120" width="230" height="90" as="geometry"/>
        </mxCell>

        <mxCell id="6" value="2.0 Book Appointment" style="ellipse;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="350" y="270" width="230" height="90" as="geometry"/>
        </mxCell>

        <mxCell id="7" value="3.0 Cancel Appointment" style="ellipse;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="350" y="420" width="230" height="90" as="geometry"/>
        </mxCell>

        <mxCell id="8" value="4.0 Conduct Consultation" style="ellipse;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="750" y="260" width="260" height="100" as="geometry"/>
        </mxCell>

        <!-- Data Stores -->
        <mxCell id="9" value="D1 Patient Record Store" style="shape=datastore;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="350" y="20" width="230" height="60" as="geometry"/>
        </mxCell>

        <mxCell id="10" value="D2 Appointment Database" style="shape=datastore;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="350" y="560" width="230" height="60" as="geometry"/>
        </mxCell>

        <!-- Data Flows -->

        <!-- Register Patient -->
        <mxCell id="11" value="Patient Application Form" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="2" target="5">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="12" value="New Patient Details" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="5" target="9">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- Book Appointment -->
        <mxCell id="13" value="Appointment Details" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="2" target="6">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="14" value="Telephone Appointment Details" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="3" target="6">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="15" value="Appointment Card" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="6" target="2">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="16" value="Appointment Record" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="6" target="10">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- Cancel Appointment -->
        <mxCell id="17" value="Cancellation Details" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="3" target="7">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="18" value="Updated Status" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="7" target="10">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- Conduct Consultation -->
        <mxCell id="19" value="Patient Record" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="9" target="8">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="20" value="Appointment List" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="10" target="8">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="21" value="Patient Record & Appointment List" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="8" target="4">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="22" value="Prescription Details" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="4" target="8">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="23" value="Printed Prescription" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;" edge="1" parent="1" source="8" target="2">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
