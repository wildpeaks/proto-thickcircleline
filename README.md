# ThickCircleLine

VRML PROTO (based on `ThickLine`) that generates a circle outline with adjustable thickness.

	EXTERNPROTO ThickCircleLine [
		exposedField  SFFloat  thickness
		exposedField  SFFloat  thicknessTesselation
		exposedField  SFFloat  radius
		exposedField  SFFloat  radiusTesselation
		field         SFFloat  creaseAngle
	] "proto.ThickCircleLine.wrl#ThickCircleLine"


-------------------------------------------------------------------------------

## Property `thickness`

Like `ThickLine.thicknessTesselation`, width of the line.

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFFloat`
 - Default Value: `0.1`


-------------------------------------------------------------------------------

## Property `thicknessTesselation`

Like `ThickLine.thicknessTesselation`, resolution of the line section (higher number = smoother tube).

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFFloat`
 - Default Value: `4`


-------------------------------------------------------------------------------

## Property `radius`

Radius of the circle.

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFFloat`
 - Default Value: `1`


-------------------------------------------------------------------------------

## Property `radiusTesselation`

Number of sides of the circle (e.g. resolution 4 = square).

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFFloat`
 - Default Value: `32`


-------------------------------------------------------------------------------

## Property `creaseAngle`

Like `Extrusion.creaseAngle`.

Definition:
 - Field Type: `field`
 - Data Type: `SFFloat`
 - Default Value: `0`


-------------------------------------------------------------------------------

