# subquery
1.  npm install -g @subql/cli
2.  subql init --starter Councillor-Proposals
3.  cd Councillor-Proposals
4.  yarn install
5.  yarn codegen
6.  yarn build
7.  docker-compose pull && docker-compose up
8.  รอ 5  นาที Open http://x.x.x.x:3000/ on your browser 

9. put code
{
  query{
    starterEntities(first:10){
      nodes{
        field1,
        field2,
        field3
      }
    }
  }
}
