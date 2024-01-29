------------
Edit B1
reload in editor
should reload ClassLibrary2
------------
Edit D1 
reload in editor
should reload ClassLibrary1 and 2
-------------
edit B1 save
swap to editor ( to be sure the reload window is open , dont click it )
edit D1 save
edit A1 save
now reload in editor
should reload all 3
------------
add 
<PackageReference Include="Stride.BepuPhysics" Version="0.9.2" />
to Demo
go to editor
reload in editor
add component should have bepu components