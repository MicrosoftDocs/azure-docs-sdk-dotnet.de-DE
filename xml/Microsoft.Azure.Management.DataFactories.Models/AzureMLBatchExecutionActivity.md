<Type Name="AzureMLBatchExecutionActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity">
  <TypeSignature Language="C#" Value="public class AzureMLBatchExecutionActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLBatchExecutionActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLBatchExecutionActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureMLBatchExecutionActivity = class&#xA;    inherit ActivityTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureMLBatchExecution")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="59512-101">Azure ML Batch Execution Service-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="59512-101">Azure ML Batch Execution Service activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLBatchExecutionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; GlobalParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GlobalParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalParameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GlobalParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59512-102">Optional.</span><span class="sxs-lookup"><span data-stu-id="59512-102">Optional.</span></span> <span data-ttu-id="59512-103">Schlüssel-Wert-Paare an die Azure ML-Batch-Ausführung-Dienstendpunkt übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="59512-103">Key,Value pairs to be passed to the Azure ML Batch Execution Service Endpoint.</span></span> <span data-ttu-id="59512-104">Schlüssel müssen mit den Webdienstparametern übereinstimmen, die im veröffentlichten Azure ML-Webdienst definiert sind.</span><span class="sxs-lookup"><span data-stu-id="59512-104">Keys must match the names of web service parameters defined in the published Azure ML web service.</span></span> <span data-ttu-id="59512-105">Werte eventuell Azure Data Factory-Funktionen zum Ausführungszeitpunkt jedes Segment (siehe http://go.microsoft.com/fwlink/?LinkId=823697) aufgelöst werden.</span><span class="sxs-lookup"><span data-stu-id="59512-105">Values may include Azure Data Factory functions to be resolved at each slice execution time (See http://go.microsoft.com/fwlink/?LinkId=823697).</span></span> <span data-ttu-id="59512-106">Werte werden in der Eigenschaft ' globalparameters ' die ausführungsanforderung für Azure ML-Batch übergeben.</span><span class="sxs-lookup"><span data-stu-id="59512-106">Values will be passed in the GlobalParameters property of the Azure ML batch execution request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceInput">
      <MemberSignature Language="C#" Value="public string WebServiceInput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WebServiceInput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInput" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceInput As String" />
      <MemberSignature Language="F#" Value="member this.WebServiceInput : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInput" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59512-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="59512-107">Optional.</span></span> <span data-ttu-id="59512-108">Der Name der Data Factory-Dataset ermöglicht die Eingabe für die Batchausführung.</span><span class="sxs-lookup"><span data-stu-id="59512-108">Name of Data Factory dataset giving the input to the batch execution.</span></span> <span data-ttu-id="59512-109">Diese Informationen werden in der WebServiceInput-Eigenschaft, die Azure ML-Batchanforderung Ausführung übergeben.</span><span class="sxs-lookup"><span data-stu-id="59512-109">This information will be passed in the WebServiceInput property of the Azure ML batch execution request.</span></span> <span data-ttu-id="59512-110">WebServiceInput kann nicht gleichzeitig mit WebServiceInputs verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="59512-110">WebServiceInput cannot be used simultaneously with WebServiceInputs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceInputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebServiceInputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebServiceInputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceInputs As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebServiceInputs : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59512-111">Optional.</span><span class="sxs-lookup"><span data-stu-id="59512-111">Optional.</span></span> <span data-ttu-id="59512-112">Schlüssel-Wert-Paaren, die Zuordnung der Namen von Azure ML Web service Eingaben für den Namen der Data Factory-Datasets.</span><span class="sxs-lookup"><span data-stu-id="59512-112">Key, Value pairs mapping the names of Azure ML web service inputs to names of Data Factory datasets.</span></span>
            <span data-ttu-id="59512-113">Die Eingabe der Batch-Ausführung wird in diesen Datasets gespeichert.</span><span class="sxs-lookup"><span data-stu-id="59512-113">The batch execution input is stored in these datasets.</span></span>
            <span data-ttu-id="59512-114">Diese Informationen werden in der WebServiceInputs-Eigenschaft, die Azure ML-Batchanforderung Ausführung übergeben.</span><span class="sxs-lookup"><span data-stu-id="59512-114">This information will be passed in the WebServiceInputs property of the Azure ML batch execution request.</span></span>
            <span data-ttu-id="59512-115">Zugeordnete Datasets muss in der Aktivität Eingaben enthalten sein.</span><span class="sxs-lookup"><span data-stu-id="59512-115">Mapped datasets must be included in the Activity's inputs.</span></span> <span data-ttu-id="59512-116">WebServiceInputs können nicht gleichzeitig mit WebServiceInput verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="59512-116">WebServiceInputs cannot be used simultaneously with WebServiceInput.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebServiceOutputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebServiceOutputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceOutputs As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebServiceOutputs : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59512-117">Optional.</span><span class="sxs-lookup"><span data-stu-id="59512-117">Optional.</span></span> <span data-ttu-id="59512-118">Schlüssel, Wert-Paare, die Namen der Data Factory-Datasets die Namen von Azure ML Web Service Ausgaben zuordnen.</span><span class="sxs-lookup"><span data-stu-id="59512-118">Key, Value pairs mapping the names of Azure ML web service outputs to names of Data Factory datasets.</span></span>
            <span data-ttu-id="59512-119">Die Ausgabe der Batch-Ausführung wird in diese Datasets nicht geschrieben.</span><span class="sxs-lookup"><span data-stu-id="59512-119">The batch execution output is written to these datasets.</span></span>
            <span data-ttu-id="59512-120">Diese Informationen werden in der Eigenschaft "webserviceoutputs" der Batchanforderung Ausführung Azure ML übergeben.</span><span class="sxs-lookup"><span data-stu-id="59512-120">This information will be passed in the WebServiceOutputs property of the Azure ML batch execution request.</span></span>
            <span data-ttu-id="59512-121">In der Aktivität Ausgaben müssen zugeordneten Datasets enthalten sein.</span><span class="sxs-lookup"><span data-stu-id="59512-121">Mapped datasets must be included in the Activity's outputs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>