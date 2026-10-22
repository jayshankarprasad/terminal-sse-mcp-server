docker build -t terminal_server_sse .

docker run --rm -p 8081:8081 -v E:/MCP/knk/workspace:/root/mcp/workspace terminal_server_sse

http://127.0.0.1:8081