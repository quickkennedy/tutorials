go into the `team fortress 2` folder and then move into the "platform" folder. <br>
then, open up `platform_misc_dir.vpk` and extract the `sourceschemebase.res` file inside the `resource` folder. <br>
open up the extracted file, and look at lines 887 through 891. <br> it should look like this:

```
FrameBorder
{
	// rounded corners for frames
	"backgroundtype" "2"
}
```
then, comment out `"backgroundtype" "2"`.<br>
then, move the file into your huds `resource` folder. <br>
your sourcescheme now has square, 90 degree coreners.
