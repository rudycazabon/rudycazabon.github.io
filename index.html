document.body.style.display = "none"; // Hide the page until it's finished rendering.

document.createElement("markdown");
var md_tags = document.getElementsByTagName("markdown"); // Returns array of all markdown tags.

for (var i = 0; i < md_tags.length; i++) { // Iterate through all the tags, and generate the HTML.
    var md_text = md_tags[i].textContent.replace(/^[^\S\n]+/mg, ""); // I love regex, so shoot me.

    var md_div = document.createElement("div"); // Make a new div to replace the fake tag.
    md_div.id = "content";
    md_div.innerHTML = marked(md_text);

    md_tags[i].parentNode.appendChild(md_div); // Add remove the old raw markdown.
    md_tags[i].parentNode.removeChild(md_tags[i]);
}

document.body.style.display = ""; // Show the rendered page.
<html lang="en-us">

<head>
    <script type="module" src="https://cdn.jsdelivr.net/gh/zerodevx/zero-md@2/dist/zero-md.min.js"></script>
    <meta charset="utf-8">
</head>

<body>
    <div style="width:70%; margin:0 auto;" id="mdcontainer">

    </div>
</body>

<script>
    function getQuery(key) {
        var query = window.location.search.substring(1);
        var key_values = query.split("&");
        var params = {};
        key_values.map(function (key_val) {
            var key_val_arr = key_val.split("=");
            params[key_val_arr[0]] = key_val_arr[1];
        });
        if (typeof params[key] != "undefined") {
            return params[key];
        }
        return "";
    }

    window.onload = function () {
        md = document.createElement("zero-md")
        md.setAttribute("src", getQuery("src"))
        md.setAttribute("no-shadow", "")
        document.getElementById("mdcontainer").append(md)
    }
</script>

</html>
