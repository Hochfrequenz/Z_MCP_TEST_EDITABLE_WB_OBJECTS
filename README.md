# Z_MCP_TEST_EDITABLE_WB_OBJECTS
The ABAP package `Z_MCP_TEST_EDITABLE_WB_OBJECTS` contains three useless ABAP workbench objects that are used for integration testing an [MCP server](https://github.com/Hochfrequenz/sapwebgui.mcp) and its use of `se24`, `se37` and `se38`:
- `ZTEST_MCP_EDIT` (a report)
- `ZCL_TEST_MCP_EDIT` (a class)
- `Z_MCP_TEST_FM` (a function module)

Developers of the MCP server should pull this into the SAP system against which they test the MCP server.
