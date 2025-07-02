# AI Prompt Suite for Public Interest Legal Practice

A comprehensive collection of 18 production-grade prompts designed to enhance legal analysis, investigation, and advocacy for public interest practitioners. These prompts enable AI-assisted workflows for human rights researchers, criminal defense attorneys, civil rights litigators, and international justice advocates.

## 🎯 Mission Statement

This prompt suite was developed to democratize access to AI-powered legal analysis tools for practitioners working in resource-constrained environments. Each prompt has been rigorously tested for reliability, bias mitigation, and adherence to professional legal standards.

## 📋 Prompt Categories

### 🔍 Investigation & Evidence Analysis
- **[Document Ingestion Early Triage](./Document_Ingestion_Early_Triage.md)** - Rapidly assess legal relevance and extract key data from documents
- **[OSINT Social-Media Scrape Triage](./OSINT_Social-Media_Scrape_Triage.md)** - Analyze social media content for evidentiary value and event clustering
- **[Witness/Testimony Analysis](./WitnessTestimony_Analysis.md)** - Evaluate witness credibility and extract verifiable claims
- **[Timeline Construction Gap Detection](./Timeline_Construction_Gap_Detection.md)** - Build chronological case timelines and identify evidentiary gaps
- **[Pattern-Based Violence Structural Abuse Detection](./Pattern-Based_Violence_Structural_Abuse_Detection.md)** - Identify systematic patterns in violence and abuse datasets

### ⚖️ International Law & Accountability
- **[Legal Framework Mapping Rome Statute CAT etc](./Legal_Framework_Mapping_Rome_Statue_CAT_etc.md)** - Map evidence to specific elements of international crimes
- **[Command Responsibility Complicity Inference](./Command_Responsibility_Complicity_Inference.md)** - Analyze command structures and infer responsibility chains
- **[Jurisdiction Accountability Strategy](./Jurisdiction_Accountability_Strategy.md)** - Develop comprehensive legal strategies for cross-border accountability
- **[Motion Drafting Argument Structuring](./Motion_Drafting_Argument_Structuring.md)** - Structure facts into persuasive legal arguments with proper citations

### 🏛️ Criminal Defense & Constitutional Rights
- **[Suppression Motion Constitutional Violation Analysis](./Suppression_Motion_Constitutional_Violation_Analysis.md)** - Identify Fourth Amendment violations for suppression motions
- **[Police Misconduct Pattern Evidence Monell Claim](./Police_Misconduct_Pattern_Evidence_Monell_Claim.md)** - Analyze misconduct patterns for federal civil rights claims
- **[Plea Offer Evaluation Alternative Strategy Generation](./Plea_Offer_Evaluation_Alternative_Strategy_Generation.md)** - Systematically evaluate plea agreements and defense alternatives
- **[Client Narrative Structuring](./Client_Narrative_Structuring.md)** - Organize client stories for mitigation and humanization strategies

### 📁 Case Management & Discovery
- **[Case Load Management Fact Summary Generation](./Case_Load_Management_Fact_Summary_Generation.md)** - Generate structured case summaries for efficient review
- **[Discovery Privilege Log Generation](./Discovery_Privilege_Log_Generation.md)** - Identify privileged materials and draft privilege logs
- **[Expert-Witness Prep Outline](./Expert-Witness_Prep_Outline.md)** - Prepare comprehensive examination outlines for expert testimony

### 🔧 Advocacy & Process Optimization
- **[Advocacy Submissions and Reparations Design](./Advocacy_Submissions_and_Reparations_Design.md)** - Draft structured submissions to international bodies and truth commissions
- **[Prompt Debugging Output Optimization](./Prompt_Debugging_Output_Optimization.md)** - Debug and optimize AI prompts for improved legal applications

## 🛡️ Reliability & Safety Features

### Built-in Quality Controls
- **Structured XML Format**: Consistent formatting prevents prompt injection and ensures reliable parsing
- **Role Integrity Protection**: Each prompt includes safeguards against role manipulation in source data
- **Citation Requirements**: Mandatory source attribution for all factual claims and legal assertions
- **Confidence Calibration**: Systematic confidence scoring helps practitioners assess AI output reliability
- **Self-Critique Mechanisms**: Built-in limitations assessment encourages critical evaluation

### Bias Mitigation
- **Cultural Sensitivity Checks**: Prompts include instructions for identifying cultural and linguistic nuances
- **Multiple Perspective Analysis**: Many prompts require consideration of alternative interpretations
- **Explicit Uncertainty Handling**: Clear protocols for managing missing or ambiguous data

## 📊 Technical Standards

### Output Formatting
- **JSON Schema Compliance**: All prompts output structured JSON for system integration
- **Consistent Citation Format**: Standardized citation schemas across all prompts
  - Documents: `[Type:Identifier, Page_#, Paragraph_#]`
  - Social Media: `[Platform:PostID]`
  - General Sources: `[source_id]`

### Confidence Taxonomies
- **Ordinal Scale**: "High", "Medium", "Low" for qualitative assessments
- **Probabilistic Scale**: 1-5 numerical ratings for likelihood and viability
- **Multi-dimensional Scoring**: Separate confidence metrics for different aspects of analysis

### Error Handling
- **Explicit Null Values**: Missing data represented as `null`, not omitted keys
- **Empty Array Standards**: Empty lists consistently represented as `[]`
- **Graceful Degradation**: Instructions for handling incomplete or corrupted input data

## 🚀 Implementation Guidelines

### Prerequisites
- AI system capable of processing XML-structured prompts
- Understanding of relevant legal frameworks and jurisdictions
- Access to qualified legal professionals for output review

### Best Practices
1. **Always Review Outputs**: AI-generated content requires human verification by qualified practitioners
2. **Maintain Source Attribution**: Preserve citation trails throughout analysis workflows
3. **Consider Context**: Adapt prompts for specific legal systems and cultural contexts
4. **Validate Confidence Scores**: Cross-reference AI confidence assessments with professional judgment

### Integration Workflows
- **Document Processing Pipelines**: Chain multiple prompts for comprehensive document analysis
- **Evidence Management Systems**: Use structured outputs to populate case management databases
- **Quality Assurance Protocols**: Implement systematic review processes for AI-assisted work products

## ⚠️ Professional Disclaimers

### Legal Limitations
- These prompts generate analytical outputs for review by qualified legal professionals
- Outputs do not constitute legal advice or establish attorney-client relationships
- All AI-generated content requires human verification and professional oversight
- Users must ensure compliance with applicable legal and ethical guidelines

### Accuracy and Liability
- AI systems may produce inaccurate, incomplete, or biased outputs
- Practitioners bear responsibility for verifying all AI-generated analysis
- Cultural, linguistic, and jurisdictional factors may affect output quality
- Regular prompt testing and validation are essential for reliable results

## 🌍 Domestic & International Applications

This prompt suite serves the full spectrum of public interest legal practice:

### Domestic Public Defense Work
- **Criminal Defense** in state and federal courts (felony, misdemeanor, appeals)
- **Public Defender Offices** managing high-volume caseloads with limited resources
- **Indigent Defense** including appointed counsel and conflict representation
- **Civil Rights Litigation** including police misconduct and constitutional violations
- **Immigration Defense** for detained and non-detained clients
- **Post-Conviction Relief** including habeas corpus and sentence modifications
- **Juvenile Defense** and family court representation
- **Mental Health Court** and specialized problem-solving courts

### International & Transitional Justice
- **International Criminal Court** proceedings and investigations
- **Universal Jurisdiction** cases in domestic courts
- **Truth and Reconciliation Commission** documentation efforts
- **Human Rights Advocacy** before UN bodies and regional courts
- **Transitional Justice** initiatives and reparations programs
- **International Legal Assistance** and capacity building
  
---
