<html>
<head>
	<title>Live2D</title>
</head>
<body>
<script src="./lib/L2Dwidget.min.js"></script>
<script>
L2Dwidget.init({
    //pluginRootPath: "./live2dw/",
    pluginJsPath: "./lib/",
    pluginModelPath: "./assets/",
    tagMode: !1,
    debug: !1,
    model: {
        scale: 2,
        jsonPath: "assets/asuna_33.model.json"
	},
    display: {
        position: "right",
        width: 180,
        height: 260,
        hOffset: 40
    },
    mobile: {
        show: !1
    },
    log: !1
})
</script>
</body>
</html>

