# Drupal Claude Code Subagents

Specialized AI agents for full stack Drupal development, designed to work with Claude Code.

## Available Agents

- **drupal-architect**: Overall Drupal architecture and project planning
- **drupal-backend-specialist**: Custom modules, APIs, and backend development
- **drupal-frontend-engineer**: Theming, templates, and frontend implementation
- **drupal-code-reviewer**: Code quality, standards, and best practices review
- **drupal-security-auditor**: Security analysis and vulnerability assessment
- **drupal-performance-optimizer**: Performance analysis and optimization

## Quick Setup for Drupal Developers

### 1. Clone or Download This Repository

```bash
git clone https://github.com/your-username/drupal-claude-subagents.git
cd drupal-claude-subagents
```

### 2. Copy Agents to Your Drupal Project

Navigate to your Drupal project directory and copy the agents folder:

```bash
cd /path/to/your/drupal/project
cp -r /path/to/drupal-claude-subagents/agents .claude/
```

**Note**: If the `.claude` folder doesn't exist in your project, create it first:

```bash
mkdir -p .claude
cp -r /path/to/drupal-claude-subagents/agents .claude/
```

### 3. Start Using the Agents

1. Open your terminal in your Drupal project directory
2. Start Claude Code: `claude`
3. There are two ways to use the agents:

#### Method 1: Let Claude Decide (Automatic Agent Selection)
Simply describe your Drupal task and Claude will automatically choose the most appropriate agent:

```
Help me create a custom content type for product listings
```

```
Review my module for security vulnerabilities
```

```
Optimize my site's performance and caching
```

#### Method 2: Explicitly Specify the Agent
Use the Task tool to invoke specific agents by name:

```
Use the drupal-backend-specialist agent to help me create a custom content type
```

```
Use the drupal-security-auditor agent to review my module for security issues
```

```
Use the drupal-performance-optimizer agent to analyze my site's performance
```

## Agent Descriptions

### drupal-architect
Best for: Project planning, architecture decisions, migration strategies, and high-level Drupal guidance.

### drupal-backend-specialist  
Best for: Custom module development, database design, API creation, and complex backend functionality.

### drupal-frontend-engineer
Best for: Theme development, template customization, CSS/JavaScript integration, and responsive design.

### drupal-code-reviewer
Best for: Code quality assessment, Drupal coding standards compliance, and best practices review.

### drupal-security-auditor
Best for: Security vulnerability analysis, access control review, and security best practices.

### drupal-performance-optimizer
Best for: Site performance analysis, caching strategies, database optimization, and performance tuning.

## Example Usage

```
Use the drupal-backend-specialist agent to help me create a custom REST API endpoint for user profiles
```

```
Use the drupal-frontend-engineer agent to help me create a responsive navigation menu theme
```

```
Use the drupal-security-auditor agent to review my user authentication module
```

## Troubleshooting

**Agents not found?**
- Ensure the `agents` folder is copied to `.claude/agents/` in your project root
- Restart Claude Code after copying the agents
- Check that you're in the correct project directory

**Agent not responding as expected?**
- Be specific about your Drupal version and requirements
- Provide context about your current setup and goals
- Try rephrasing your request with more details
