<mxfile host="app.diagrams.net">
  <diagram name="Context Diagram Level 0">
    <mxGraphModel dx="1000" dy="600" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1100" pageHeight="850">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>

        <!-- Central Process -->
        <mxCell id="2" value="Doctors' Clinic System" style="ellipse;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="400" y="250" width="250" height="120" as="geometry"/>
        </mxCell>

        <!-- Patient -->
        <mxCell id="3" value="Patient" style="rounded=0;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="100" y="200" width="150" height="80" as="geometry"/>
        </mxCell>

        <!-- Front Desk Officer -->
        <mxCell id="4" value="Front Desk Officer" style="rounded=0;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="100" y="350" width="180" height="80" as="geometry"/>
        </mxCell>

        <!-- Doctor -->
        <mxCell id="5" value="Doctor" style="rounded=0;whiteSpace=wrap;html=1;strokeWidth=2;" vertex="1" parent="1">
          <mxGeometry x="750" y="250" width="150" height="80" as="geometry"/>
        </mxCell>

        <!-- Data Flows -->

        <!-- Patient to System -->
        <mxCell id="6" value="Application Form / Appointment Request" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;html=1;" edge="1" parent="1" source="3" target="2">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- System to Patient -->
        <mxCell id="7" value="Appointment Card / Prescription" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;html=1;" edge="1" parent="1" source="2" target="3">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- Front Desk to System -->
        <mxCell id="8" value="Telephone Booking / Cancellation Details" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;html=1;" edge="1" parent="1" source="4" target="2">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- Doctor to System -->
        <mxCell id="9" value="Prescription Details / Record Request" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;html=1;" edge="1" parent="1" source="5" target="2">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- System to Doctor -->
        <mxCell id="10" value="Patient Record / Appointment List" style="edgeStyle=orthogonalEdgeStyle;endArrow=block;html=1;" edge="1" parent="1" source="2" target="5">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
