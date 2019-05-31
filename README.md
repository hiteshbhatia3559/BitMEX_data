# BitMEX_data
Data retrieved from the Bitmex orderbook for XBTUSD and XBT June Futures

Data is committed automatically every day at 12:00AM IST. Timestamps are BitMEX server timestamps, and all data provided is as received by pinging the server every one second. Lower timeframes can be obtained by setting up the BitMEX delta server yourself (and then sending get requests to it as an API would function but without a rate limit).

Link to BitMEX delta server : https://github.com/BitMEX/api-connectors/tree/master/official-ws/delta-server

Note : If granular tick by tick data is your requirement, it is also available free of cost here : https://public.bitmex.com/?prefix=data/trade/

Game on.
