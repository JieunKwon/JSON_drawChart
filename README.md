# JSON_drawChart
Draw chart with JSON data

Canvas 
-----

- Property	Description

fillStyle	- Sets or returns the color, gradient, or pattern used to fill the drawing

strokeStyle	- Sets or returns the color, gradient, or pattern used for strokes

shadowColor	- Sets or returns the color to use for shadows

shadowBlur	- Sets or returns the blur level for shadows

shadowOffsetX	- Sets or returns the horizontal distance of the shadow from the shape

shadowOffsetY	- Sets or returns the vertical distance of the shadow from the shape


    myChart = new Chart(ctx).Line(chartData);
    
    		var chartData = {
				labels : ["Jan", "Feb", "Mar", "Apr", "May"],
				datasets: [
					{
            // color is optional, if not, default is grey
            // R,G,B color, gradient(0 ~ 1) 
            fillColor : "rgba(37, 94, 177, 0.5)",
            strokeColor : "rgba(0, 0, 0, 1)",
            pointColor : "rgba(255, 0, 0, 1)",
            pointStrokeColor : "#fff",

            // mandatory data information
            data : [65, 59, 40, 81, 56]
          }
				]
			}
