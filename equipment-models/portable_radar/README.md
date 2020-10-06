# Portable Radar - *portable_radar*
> Originally from Call of Duty: Modern Warfare 3

This model is a recreation of the "portable radar"'s model.

## documentation
Returns a dictionary:
- **Model** *model*
> the model
- **Part** *base*
> the base of the model
- **Array**<**Part**> *objects*
> the objects in the model
- **Function**<**Model**> *clone*(*void*)
> returns a clone of the model with all parts unanchored

## notes
Model properties:
- welded
- PrimaryPart is set - base

Part properties:
- anchored
- **NOT** massless
- do not collide, **base has CanCollide enabled**

Other notes:
- has BodyGyro to constantly make model face up

## projects i used this in
> as of 20.10.06

### Call of Phantoms (CREATION)
- Used as the model for the portable radar equipment

# Usage
ALL ARE ALLOWED TO USE THIS MODEL, IN ANY WAY (SCRIPT AND TOOLBOX INCLUDED)
