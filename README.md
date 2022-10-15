# test-archieve
test-archieve



curl --request GET \
  --url 'https://prasanna-test.atlassian.net/rest/api/3/issue/SAM-1/transitions' \
  --user 'prasannaramesh2000@gmail.com:RHJZxYsxBDtgSinubKL8404D' \
  --header 'Accept: application/json'

curl --request POST \
  --url 'https://prasanna-test.atlassian.net/rest/api/3/issue/SAM-1/transitions' \
  --user 'prasannaramesh2000@gmail.com:RHJZxYsxBDtgSinubKL8404D' \
  --header 'Accept: application/json' \
  --header 'Content-Type: application/json' \
  --data '{
  "transition": {
    "id": "31"
  }}'