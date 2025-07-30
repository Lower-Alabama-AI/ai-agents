# Claude Agent Templates

A comprehensive collection of role-based AI agent templates designed to transform Claude into specialized team members for software development projects. These battle-tested templates provide structured personas that deliver consistent, high-quality assistance across various technical and creative domains.

NOTE: To Contribute to this reop please see: https://github.com/Lower-Alabama-AI/ai-agents/blob/main/CONTRIBUTING.md

## Overview

These templates go beyond simple prompts - they're complete role definitions that include:
- **Core responsibilities** and domain expertise
- **Thinking patterns** and problem-solving approaches
- **Key questions** to ask at each project phase
- **Standards** to enforce and maintain
- **Communication styles** optimized for each role
- **Portfolio-specific** knowledge and patterns

## Available Roles

### 🏗️ **Software Architect**
Strategic system design and technical decision-making expert who focuses on scalability, integration, and long-term technical vision.
- System architecture and design patterns
- Technology stack evaluation
- Cross-project synergies
- Risk assessment and mitigation

### 💻 **Software Developer**
Hands-on coding expert proficient in modern development practices across frontend and backend technologies.
- Feature implementation
- Code quality and testing
- Performance optimization
- Debugging and problem-solving

### 🔧 **DevOps Engineer**
Infrastructure and deployment specialist ensuring reliable, scalable, and secure operations.
- CI/CD pipeline management
- Cloud infrastructure
- Monitoring and alerting
- Security best practices

### 📝 **Document Writer**
User-focused content creator specializing in clear, helpful documentation and learning materials.
- User guides and tutorials
- API documentation
- Help system design
- Knowledge base management

### 📊 **Product Manager**
Strategic product leader balancing user needs, business objectives, and technical constraints.
- Product strategy and roadmapping
- User research and validation
- Stakeholder management
- Data-driven decision making

### 🔍 **QA Engineer**
Quality champion ensuring robust, user-friendly software through comprehensive testing strategies.
- Test planning and execution
- Bug tracking and validation
- Performance testing
- User acceptance criteria

### 🔒 **Security Engineer**
Security-first mindset protecting systems and data through proactive threat modeling and defense.
- Security architecture
- Vulnerability assessment
- Compliance management
- Incident response planning

### 🎨 **UI/UX Designer**
User experience advocate creating intuitive, accessible, and visually appealing interfaces.
- User research and journey mapping
- Interface design and prototyping
- Accessibility compliance
- Design system management

## How to Use

### Basic Implementation

1. **Copy the template** you need from the `roles/` directory
2. **Add to your project** in a `.claude/` directory
3. **Customize for your needs** by adding project-specific context
4. **Activate the role** by including it in your conversation with Claude

### Example Usage

```markdown
You are acting as a Software Architect for my project. 

[Paste the architect.md template content here]

Now, help me design the authentication system for my new SaaS application.
```

### Advanced Implementation

For more sophisticated agent systems, consider:

1. **Session Protocols** - Add initialization and cleanup routines
2. **Memory Banks** - Create persistent context files
3. **Project Integration** - Reference specific codebases and documentation
4. **Multi-Agent Coordination** - Have agents work together on complex tasks

## Template Structure

Each template follows a consistent structure:

```markdown
# [Role] Role

## Core Responsibilities
- Primary duties and focus areas

## [Role] Mindset
- How this role thinks about problems
- Key perspectives and approaches

## Key Questions I Ask
- Strategic questions for discovery
- Technical validation questions
- Risk and quality considerations

## Standards I Enforce
- Quality benchmarks
- Best practices
- Compliance requirements

## Communication Style
- How to interact with stakeholders
- Documentation approach
- Collaboration methods
```

## Customization Guide

### Project-Specific Adaptations

Transform generic templates into project-specific agents by adding:

1. **Technology Stack Context**
   ```markdown
   ## Project Technologies
   - Frontend: React, TypeScript, Tailwind CSS
   - Backend: Python FastAPI, PostgreSQL
   - Infrastructure: AWS, Docker, GitHub Actions
   ```

2. **Business Domain Knowledge**
   ```markdown
   ## Domain Context
   - Industry: Financial Services
   - Compliance: SOC2, PCI-DSS
   - User Base: Enterprise B2B
   ```

3. **Current Project State**
   ```markdown
   ## Project Status
   - Phase: Pre-launch beta
   - Critical Path: Payment integration
   - Technical Debt: Legacy authentication system
   ```

### Creating New Roles

To create a custom role:

1. Start with the most similar existing template
2. Define the core value proposition
3. List specific responsibilities
4. Document thinking patterns
5. Add domain-specific expertise
6. Test with real project scenarios

## Best Practices

### ✅ DO
- **Provide context** about your project when using templates
- **Combine roles** for complex tasks requiring multiple perspectives
- **Iterate and refine** templates based on actual usage
- **Document customizations** for team consistency
- **Share improvements** back to the community

### ❌ DON'T
- Don't use templates without reading them first
- Don't expect perfect results without project context
- Don't ignore the communication style guidelines
- Don't use single roles for tasks requiring multiple expertise areas

## Integration Examples

### With Claude Projects
```markdown
1. Create a new Claude Project
2. Add your codebase as project knowledge
3. Include relevant role templates
4. Reference both in your conversations
```

### With Development Workflows
```markdown
- Code Review: Use Developer + QA Engineer roles
- Architecture Decision: Use Architect + Security Engineer roles
- Feature Planning: Use Product Manager + UI/UX Designer roles
- Documentation: Use Document Writer + Developer roles
```

## Community and Contributions

### Contributing
We welcome contributions! To add new templates or improve existing ones:

1. Fork the repository
2. Create a new branch for your changes
3. Follow the existing template structure
4. Include real-world usage examples
5. Submit a pull request with clear description

### Sharing Custom Roles
If you've created specialized roles for your domain (e.g., Data Scientist, Marketing Strategist, Legal Advisor), please consider contributing them to help others in similar fields.

## License

MIT License - Feel free to use, modify, and distribute these templates in your projects.

## Acknowledgments

These templates were developed through extensive real-world usage across multiple production projects including:
- SaaS platforms
- Mobile applications  
- Enterprise tools
- AI/ML systems
