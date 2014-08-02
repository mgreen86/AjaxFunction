AjaxFunction
============

My standard Ajax implementation

    function loadResponse() {
        var ajax = function () {
                return $.get('url');
            };
            ajax().then(function (data) {


            });
    }
