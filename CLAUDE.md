# Claude Code Instructions

## Purpose
This repository aggregates technical information about DTC (Direct to Cell, D2C) communication services, particularly au Starlink Direct.

**Note**: Information in this repository is based on unofficial research and analysis, not official specifications.

## Guidelines
- **Documentation focus**: This workspace is primarily for documentation, not code development
- **Minimize code generation**: Prioritize documentation tasks over code generation
- **Language**: Use Japanese for all documentation
- **Content scope**: Focus on DTC technology overview, au Starlink Direct, technical specifications, and implementation details

## Documentation Style
- **User-first approach**: Start with user-facing information (what happens, when it happens, how to fix it)
- **Technical details last**: Include technical details at the end after practical information
- **Screenshots support**: Prepare placeholder sections for screenshots to support explanations
- **Clear structure**: Use clear headings and sections to separate user information from technical details

### Problem-solving document structure (based on current-issues.md)
Recommended structure for documenting DTC-related issues and problems:

1. **Problem overview**: Clear description of what happens
2. **Occurrence conditions**: Specific situations when it happens
3. **Root cause explanation**: Background of why it happens
4. **Testing environment**: 
   - Confirmed devices (model)
   - Software environment (Android version, app version)
   - Confirmation date
5. **Screenshots**: Comparison images of normal vs problematic behavior
6. **Solutions and workarounds**: 
   - Reliable solutions (in recommended order)
   - Explicitly mention ineffective methods
7. **Important notes**: Clarification when it's not a service issue itself
8. **Technical details**: Root cause analysis and technical background

## Technical Knowledge Base
- **Android airplane mode behavior**: Android disables DTC communication when airplane mode is enabled, so airplane mode cannot be used to force DTC-only connection
- **DTC vs terrestrial network switching**: Android uses isNonTerrestrialNetwork flag to determine communication method, but the switching logic can cause issues in border areas