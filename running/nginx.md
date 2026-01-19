# Nginx Must-Know Topics

## [1. Introduction & Basics](#)
  - [What is Nginx](#)
  - [Nginx vs Apache](#)
  - [Installation & setup](#)

## [2. Core Configuration](#)
  - [Main config files (`nginx.conf`, `sites-available`, `sites-enabled`)](#)
  - [Contexts: `main`, `http`, `server`, `location`](#)
  - [Directives vs Blocks](#)
  - [Include directive](#)

## 3. HTTP Server
  - Serving static files
  - MIME types
  - Default server block
  - Index files
  - Autoindex

## 4. Server Blocks (Virtual Hosts)
  - Name-based virtual hosting
  - IP-based virtual hosting
  - Default server

## 5. Location Matching
  - Prefix (`/path/`)
  - Exact match (`=`)
  - Regex (`~`, `~*`)
  - Priority rules

## [6. Reverse Proxy & Load Balancing](#)
  - [`proxy_pass`](#)
  - [Proxy headers (`X-Forwarded-*`)](#)
  - [Load balancing methods (round-robin, least_conn, ip_hash)](#)
  - [Health checks](#)

## 7. Security
  - SSL/TLS setup (certificates, `ssl_certificate`, `ssl_certificate_key`)
  - Redirect HTTP → HTTPS
  - Rate limiting (`limit_req`)
  - Connection limiting (`limit_conn`)
  - Restricting access (`allow`, `deny`)
  - Basic authentication

## 8. Performance Optimization
  - Gzip compression
  - Caching (proxy cache, microcaching)
  - Browser caching (`expires`, `cache-control`)
  - Keepalive connections
  - Worker processes & connections tuning

## 9. Logging & Monitoring
  - Access log format
  - Error logs
  - Log rotation
  - Stub status module (basic monitoring)
  - Integration with monitoring tools

## 10. Advanced Features
  - Rewrite & Redirect rules
  - URL rewriting with `rewrite`
  - Redirect with `return`
  - FastCGI (PHP-FPM)
  - Upstream servers
  - Stream (TCP/UDP load balancing)
  - WebSocket proxying

## 11. Modules & Extensibility
  - Built-in modules
  - Dynamic modules
  - Third-party modules

## 12. Deployment & Management
  - Testing config (`nginx -t`)
  - Reload vs Restart
  - Zero-downtime reload
  - Common pitfalls

## 13. Real-world Scenarios
  - Reverse proxy for Node.js/Python apps
  - Hosting multiple websites
  - Load balancing multiple backends
  - Securing API endpoints
  - Serving React/Vue/Angular single-page apps
