#HTML Structure View
A simple and useful tool to assist in planning, presentation and visualization of structures of your site.

##Demonstration
http://thiagodini.com/html-structure-view/demo.html

[HTML Structure View](javascript: (function () { var htmlstructureview = document.createElement('link'); var head = document.getElementsByTagName('head')[0]; var link = document.getElementsByTagName('link'); for(var i = 0; i <= link.length; i++){ head.removeChild(link[0]); } htmlstructureview.rel = 'stylesheet'; htmlstructureview.href = 'http://thiagodini.com/html-structure-view/viewer.css'; head.appendChild(htmlstructureview);})();)
