Paste following code to http://mdaines.github.io/viz.js/

```
digraph Demos_ASPNET5_Project_Dependence {

	"MyHealth.Data" -> "MyHealth.Model";
	"MyHealth.API" -> "MyHealth.Model";
	"MyHealth.API" -> "MyHealth.Data";
	"MyHealth.API" -> "MyHealth.Office365";
	"MyHealth.Office365" -> "MyHealth.Model";
	"MyHealth.Web" -> "MyHealth.Model";
	"MyHealth.Web" -> "MyHealth.Data";
	"MyHealth.Web" -> "MyHealth.API";
	"MyHealth.Web" -> "MyHealth.Office365";
	
}
```
