input태그의 maxlength는 type이 text, email, password 등에만 적용되고 number type은 안됨.

방법) oninput 이벤트

<input type="number" oninput="maxLengthCheck(this)" maxlength="4" >

<script>   
function maxLengthCheck(object){
    if (object.value.length > object.maxLength){
      object.value = object.value.slice(0, object.maxLength);
    }    
}
</script>
