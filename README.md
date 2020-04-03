$.ajax({
    url: https://github.com/freelancerMizan/api/blob/master/users.json,
    dataType: 'jsonp',
    success: function(results)
    {
        var content = results.data.content;
    });
