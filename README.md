# ir
curl -X 'POST'
'https://langchain-3ff4ab2c9d.wolf.jina.ai/ask_url'
-H 'accept: application/json'
-H 'Content-Type: application/json'
-d '{ "url": "https://uiic.co.in/sites/default/files/uploads/downloadcenter/Arogya%20Sanjeevani%20Policy%20CIS_2.pdf", "question": "What'''s the cap on room rent?", "envs": { "OPENAI_API_KEY": "'"${OPENAI_API_KEY}"'" } }'

{"result":" Room rent is subject to a maximum of INR 5,000 per day as specified in the Arogya Sanjeevani Policy [Page no. 1].","error":"","stdout":""}
