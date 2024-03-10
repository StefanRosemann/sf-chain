# sf-chain

# start-cmd:
npm run dev
HTTP_PORT=3002 P2P_PORT=5002 PEERS=ws://localhost:5001 npm run dev
HTTP_PORT=3003 P2P_PORT=5003 PEERS=ws://localhost:5001,ws://localhost:5002 npm run dev

# REST-API
GET: localhost:3001/blocks

POST: localhost:3001/mine
{
"data": "bar"
}

GET:  localhost:3001/transactions

POST: localhost:3001/transact
{
	"recipient": "foo-4dr3ss",
	"amount": 50
}

GET: localhost:3001/public-key



