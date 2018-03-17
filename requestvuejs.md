## HTTP request

**AJAX** = JavaScript asynchrone et XML  
ensemble d'outils utilisés pour tirer parti des capacité asynchrone de JS

Il ya 4 méthodes de requêtes : GET POST DELETE PUT


### XHR GET REQUEST

    const xhr = new XMLHttpRequest();
    const url = 'https://api-to-call.com/endpoint';
    xhr.responseType = 'json';

    xhr.onreadystatechange = function(){
        if (xhr.readyState === XMLHttpRequest.DONE) {
	        console.log(xhr.response)
        }
  
    }
    xhr.open('GET', url);
    xhr.send();


### XHR POST REQUEST  

    const xhr = new XMLHttpRequest();
    const url = 'https://api-to-call.com/endpoint';
    const data = JSON.stringify({id: '200'});
    xhr.responseType = 'json';

    xhr.onreadystatechange = function(){
        if(xhr.readyState === XMLHttpRequest.DONE){
            console.log(xhr.response);
        }
    }

    xhr.open('POST', url);
    xhr.send(data);

### AJAX GET REQUEST


    $.ajax({
        url :'https://api-to-call.com/endpoint',
        type : 'GET',
        dataType : 'json',

        success(response){
            console.log(response);
        },

        error(jqXHR,status,errorThrown){
                console.log(jqXHR);
        }
    });

### AJAX POST REQUEST  

    $.ajax({
         url :'https://api-to-call.com/endpoint',
        type : 'POST',
        data : JSON.stringify({id: 200}),
        dataType : 'json',
  
        success (response){
            console.log(response)
        },
  
        error(jqXHR,status,errorThrown){
            console.log(jqXHR)
        }
    });

### AJAX requests with $.get()

    $.get('https://api-to-call.com/endpoint', response => {...}, 'json');

    AUTRE EX : 

    $.get(urlToExpand, response => {$responseField.append('<p>Your expanded url is: </p><p>' + response.longUrl + '</p>')},'json');

### AJAX requests with $.post()  

    $.post('https://api-to-call.com/endpoint', {data}, response => {...}, 'json');


### AJAX Requests with $.getJSON()  

    $.getJSON(urlToExpand, response => {$responseField.append('<p>Your expanded url is: </p><p>' +  response.longUrl + '</p>')});