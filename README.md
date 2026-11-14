

[![mcptry](https://mcptry.com/badge/com.massageinchina/mcp)](https://mcptry.com/servers/com.massageinchina/mcp)
[![MCPRush Listing](https://mcprush.com/badge/massageinchina-authentic-tcm-tuina-acupressur-mcp/card.svg)](https://mcprush.com/to/massageinchina-authentic-tcm-tuina-acupressur-mcp?ref=badge)

[![Official Website](https://img.shields.io/badge/Website-massageinchina.com-blue)](https://massageinchina.com)
[![MCP Registry](https://img.shields.io/badge/MCP_Registry-com.massageinchina%2Fmcp-green)](https://www.mcptry.com/servers/com.massageinchina/mcp)
[![Glama Connector](https://img.shields.io/badge/Glama-Connector-purple)](https://glama.ai/mcp/connectors/com.massageinchina/mcp)

Look up Traditional Chinese Medicine (TCM) Tuina massage styles, meridian acupoints & phrases.

- **Official Workbench**: [https://massageinchina.com](https://massageinchina.com)
- **Remote MCP Endpoint**: `https://massageinchina.com/api/mcp` (`streamable-http`, read-only, no API key required)
- **Public OpenAPI 3.0**: [https://massageinchina.com/openapi.json](https://massageinchina.com/openapi.json)
- **LLM Context**: [https://massageinchina.com/llms.txt](https://massageinchina.com/llms.txt) · [https://massageinchina.com/llms-full.txt](https://massageinchina.com/llms-full.txt)

## Tools Provided (4 Read-Only Tools)

| Tool Name | Summary |
| :--- | :--- |
| `lookup_tcm_acupoints_and_tuina` | Look up Traditional Chinese Medicine (TCM) Tuina massage modalities, blind clinical massage (Mangren Anmo), meridian acupoints, and RMB pricing. |
| `generate_mandarin_massage_phrase_card` | Generate ready-to-show Chinese character and Pinyin communication cards for adjusting pressure, specifying sore areas, or declining add-ons. |
| `compare_china_massage_venue_types` | Compare clinical rigor, typical RMB cost, tipping norms (zero tipping), and booking workflow across Chinese massage venue categories. |
| `check_tuina_cupping_contraindications` | Check medical contraindications and travel timing tips before receiving deep orthopedic Tuina, fire cupping, or Gua Sha. |

## Connect in 10 Seconds

### Claude Code
```bash
claude mcp add --transport http massageinchina https://massageinchina.com/api/mcp
```

### Cursor / Claude Desktop / Windsurf (`mcp.json`)
```json
{
  "mcpServers": {
    "massageinchina": {
      "type": "streamable-http",
      "url": "https://massageinchina.com/api/mcp"
    }
  }
}
```

### Agent Skill (`skills.sh`)
```bash
npx -y skills@latest add AbigailDavised/massageinchina-mcp -y
```

## License

MIT © [MassageInChina](https://massageinchina.com)
