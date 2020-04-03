$.ajax({
    url: https://github.com/freelancerMizan/api/new/master?readme=1,
    dataType: 'jsonp',
    success: function(results)
    {
        var content = results.data.content;
    });
