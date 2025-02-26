# User Guide
************************************************
## Table of Contents

**1. Getting Started**
* 1.1 [Introduction](1_1_Introduction.md)
* 1.2 [Installation](1_2_Installation.md)
* 1.3 [Quick Start](1_3_Quick_Start.md)
* 1.5 [ApplicationStructure](1_4_Application_Engineering_Structure_Explanation.md)

**2. Principle Introduction**

* 2.1 Framework Principles
* 2.2 [Domain Components](2_2_Domain_Component_Principles.md)
  * 2.2.1 [Agent](2_2_1_Agent.md)
    * 2.2.1.1 [Create And Use](2_2_1_Agent_Create_And_Use.md)
    * 2.2.1.2 [Related Domain Objects](2_2_1_Agent_Related_Domain_Objects.md)
  * 2.2.2 [LLM](2_2_2_LLM.md)
    * 2.2.2.1 [Define And Use](2_2_2_LLM_component_define_and_usage.md)
    * 2.2.2.2 [Related Domain Objects](2_2_2_LLM_Related_Domain_Objects.md)
  * 2.2.3 [Tool](2_2_3_Tool.md)
    * 2.2.3.1 [Create And Use](2_2_3_Tool_Create_And_Use.md)
    * 2.2.3.2 [Related Domain Objects](2_2_3_Tool_Related_Domain_Objects.md)
  * 2.2.4 [Knowledge](2_2_4_Knowledge.md)
    * 2.2.4.1 [Define And Use](2_2_4_Knowledge_Define_And_Use.md)
    * 2.2.4.2 [Related Domain Objects](2_2_4_Knowledge_Related_Domain_Objects.md)
  * 2.2.5 [Memory](2_2_5_Memory.md)
    * 2.2.5.1 [Define And Use](2_2_5_Memory_Define_And_Use.md)
    * 2.2.5.2 [Related Domain Objects](2_2_5_Memory_Related_Domain_Objects.md)
  * 2.2.6 [Planner](2_2_6_Planner.md)
    * 2.2.5.1 [Define And Use](2_2_6_Planner_Define_And_Use.md)
    * 2.2.5.2 [Related Domain Objects](2_2_6_Planner_Related_Domain_Objects.md)
* 2.3 Technical Components
  * 2.3.1 [RAG](2_2_4_RAG.md)
    * 2.3.1.1 [How To Build A RAG Agent](2_2_4_How_To_Build_A_RAG_Agent.md)
* 2.4 Others
  * 2.4.1 Service
    * 2.4.1.1 [Registration and Usage](2_4_1_Service_Registration_and_Usage.md)
    * 2.4.1.2 [Web Server](2_4_1_Web_Server.md)
    * 2.4.1.3 [Web API](2_4_1_Web_Api.md)
    * 2.4.1.4 [Service Information Storage](./2_4_1_Service_Information_Storage.md)
  * 2.4.2 Prompt Management
  * 2.4.3 Multi-turn Dialogue
  * 2.4.4 Logging
    * 2.4.4.1 [Logging Component](2_6_Logging_Utils.md)
  * 2.4.5 Data Collection
    * 2.4.5.1 [Monitor Module](2_5_1_Monitor_Module.md)
  * 2.4.6 Data Autonomous
    * 2.4.6.1 [Data Autonomous Agent](8_1_1_data_autonomous_agent.md)

**3. Component Reference Manual**
* 3.1 Domain Components
  * 3.1.1 List of Agents
  * 3.1.2 [List of LLMs](3_1_2_0_List_Of_LLMs.md)
    * 3.1.2.1 [OpenAI Usage Instructions](3_1_2_OpenAI_LLM_Use.md)
    * 3.1.2.2 [Qwen Usage Instructions](3_1_2_Qwen_LLM_Use.md)
    * 3.1.2.3 [WenXin Usage Instructions](3_1_2_WenXin_LLM_Use.md)
    * 3.1.2.4 [Kimi Usage Instructions](3_1_2_Kimi_LLM_Use.md)
    * 3.1.2.5 [BaiChuan Usage Instructions](3_1_2_BaiChuan_LLM_Use.md)
    * 3.1.2.6 [Claude Usage Instructions](3_1_2_Claude_LLM_Use.md)
    * 3.1.2.7 [Ollama Usage Instructions](3_1_2_Ollama_LLM_Use.md)
    * 3.1.2.8 [DeepSeek Usage Instructions](3_1_2_DeepSeek_LLM_Use.md)
    * 3.1.2.9 [GLM Usage Instructions](3_1_2_GLM_LLM_Use.md)
    * 3.1.2.10 [General OpenAI Protocol Style Wrapper](3_1_2_OpenAIStyleLLM_Use.md)
  * 3.1.3 List of Tools
    * 3.1.3.1 [Integration Tool Details](2_2_3_Integrated_Tools.md)
    * 3.1.3.2 [LangChain Tool Wrapper](2_2_3_Integrated_LangChain_Tools.md)
  * 3.1.4 List of Knowledge
  * 3.1.5 List of Memories
  * 3.1.6 List of Planners
* 3.2 Technical Components
  * 3.2.1 RPC
    * 3.2.1.1 [gRPC](3_2_1_gRPC.md)
  * 3.2.2 Store
    * 3.2.2.1 [SQLDBWrapper](2_3_1_SQLDB_WRAPPER.md)
    * 3.2.2.2 [Milvus](3_3_1_Milvus.md)
    * 3.2.2.3 [ChromaDB](3_3_2_ChromaDB.md)
    * 3.2.2.4 [Sqlite](3_3_3_Sqlite.md)
  * 3.2.3 Msg
  * 3.2.4 Logging
    * 3.2.4.1 [Alibaba Cloud SLS](3_2_4_Alibaba_Cloud_SLS.md)

**[4. API Reference Manual](4_1_API_Reference.md)**

**5. Best Practices**
* 5.1 Operations and Deployment
  * 5.1.1 [Docker Containerization Solution](5_1_1_Docker_Container_Deployment.md)
  * 5.1.2 [K8S Solution](5_1_2_K8S_Deployment.md)

**6. Use Cases**
* 6.1 RAG-Type Agent Examples
  * 6.1.1 [Legal Consultation Agent v2](7_1_1_Legal_Consultation_Case.md)
* 6.2 ReAct-Type Agent Examples
  * 6.2.1 [Python Code Generation and Execution Agent](7_1_1_Python_Auto_Runner.md)
* 6.3 [Discussion Group Based on Multi-Turn Multi-Agent Mode](6_2_1_Discussion_Group.md)
* 6.4 PEER Multi-Agent Cooperation Examples
  * 6.4.1 [Financial Event Analysis Case](./6_4_1_Financial_Event_Analysis_Case.md)
* 6.5 [Andrew Ng's Reflexive Workflow Translation Agent Replication](./7_1_1_Translation_Case.md)

**7.Product Platform**
* 7.1 [Quick Use](./10_1_1_Product Platform Quick Start.md)
* 7.2 [Advancement Guide](./10_1_2_Product_Platform_Advancement_Guide.md)

**8. Series of Articles**

**9. Frequently Asked Questions (FAQ)**

**[10.Citation](9_1_Citation.md)**

**[11. Contact Us](6_1_Contact_Us.md)**
