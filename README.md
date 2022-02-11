# Regular-Expression

https://velog.io/@fstone/%EC%A0%95%EA%B7%9C%ED%91%9C%ED%98%84%EC%8B%9D-%EC%A0%95%EB%A6%AC


#phone number

const autoHyphen = (target) => {
 target.value = target.value
   .replace(/[^0-9]/, '')
   .replace(/^(\d{2,3})(\d{3,4})(\d{4})$/, `$1-$2-$3`);
}
