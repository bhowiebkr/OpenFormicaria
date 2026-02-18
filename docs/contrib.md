# How to expand OpenFormicaria

There are several processes and standards within this project, so let's have a look at them.

Use an existing CAD file as reference when creating new parts. All new designs should follow the CV2 connector standard.

You can find the repository here: [Github](https://github.com/schemen/OpenFormicaria)

Fork it and add your changes.

## How to PR/MR on Github

When you have a creation you want to have added, make sure it is in the correct folder (STL exports, CAD files etc.).
Add the documentation of your part in to `docs` folder as well.

Please create PRs into the **devel** branch!

## Base structural blocks for any modules

A base block has the size of **35mmx35mmx20mm**. The 4xGateway has essentially those measurements. This square is essentially the base block size for connector facing faces.

You can see this with the 6xGateway. On a side, they have two connector placements, this side has to be 70mm wide to fit both of them. A face that does not intend to have connectors, you are free to move out of this size. The example here would be the Portal — the face with the feeder holes is a bit outside of this box.

### Some other specs to modules

- The glass cut out is 3mm deep
- The M3 screw holes have a radius of 1.4mm
- The ant "cutout" is recommended to be around 15mm deep. This leads to a 2mm floor with 20mm total height.
- To hold the glass I've used a 1mm wide ledge so far

## Connector

Please have a look at the folder `Measurements` with all the detailed measurements on how the connector looks like.

A connector is set up with the following parts:

- Female connector is on all modules. The hole cut through has a radius of **5mm** and is centered. The female has a Hill in the center — check `ConnectorV2_Hill` for its specs.
- Male connectors are standalone and are used in between to connect all modules. The male has a groove and a rail so that the Hill can slide and lock. Check out the images `ConnectorV2_Rail` and `ConnectorV2_Groove` for the specs.

## Formicaria

The formicaria are created in two steps:

**1)** A template is created and maintained for each size. This template is empty and does not have any ant digging site, just free space. This gets exported as STL.

**2)** In Photoshop or any editor of your preference a black/white plan of the ant pathways is drawn. This then gets imported in 3D Builder and placed into the template, combining the two.

This approach allows to create many different inserts for the formicaria for different ant species. You can of course further customize the templates if you wish.

Have a look at `Formicaria/Inserts/` to find PSD templates and already generated ant styles.

## Helping in other ways

If you like the design and all the work that already went in, you could consider supporting the original author at [Buymeacoffee](https://www.buymeacoffee.com/schemen) as a motivator!
