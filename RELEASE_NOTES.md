# kill-process-mcp release notes

This is a high-level summary of the most important changes.

# Changes in 1.0 (01 Jul 2025)

**Features and Improvements**:

- **NEW:** Introduced MCP `process_list` tool to list running processes with optional filtering, sorting and limit
- **NEW:** Introduced MCP `process_kill` tool to kill the selected process
- **NEW:** Implemented macOS-only helper for Activity Monitor-style physical memory reporting with fallback to RSS and USS memory metrics on Windows and Linux
- **IMPROVE:** Excluded processes owned by system users by default
