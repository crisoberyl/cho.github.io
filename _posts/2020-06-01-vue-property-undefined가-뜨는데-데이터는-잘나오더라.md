선언하는 순서가 어쩌고....  
잘 모르겠어서...  
그냥 이 오류만 눈앞에서 치우고싶었다.  
그래서 검색해본 결과  
The console will Cannot read property ‘xxx’ of undefined before the backend content is returned.  
따라서 



 `v-if="foo"`  
 
 
 
 해주거나  
 
 
 
            new Vue({
              foo: {
                title: '',
                description : ''
              },
              created(){
                / / Call the backend interface
              }
            });
            


이렇게 해주면 된다고 함!




