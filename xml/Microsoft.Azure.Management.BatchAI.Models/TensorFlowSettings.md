<Type Name="TensorFlowSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings">
  <TypeSignature Language="C#" Value="public class TensorFlowSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TensorFlowSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class TensorFlowSettings" />
  <TypeSignature Language="F#" Value="type TensorFlowSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="07665-101">Gibt die Einstellungen für TensorFlow Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="07665-101">Specifies the settings for TensorFlow job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TensorFlowSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07665-102">Initialisiert eine neue Instanz der TensorFlowSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07665-102">Initializes a new instance of the TensorFlowSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TensorFlowSettings (string pythonScriptFilePath, string masterCommandLineArgs, string pythonInterpreterPath = null, string workerCommandLineArgs = null, string parameterServerCommandLineArgs = null, Nullable&lt;int&gt; workerCount = null, Nullable&lt;int&gt; parameterServerCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string pythonScriptFilePath, string masterCommandLineArgs, string pythonInterpreterPath, string workerCommandLineArgs, string parameterServerCommandLineArgs, valuetype System.Nullable`1&lt;int32&gt; workerCount, valuetype System.Nullable`1&lt;int32&gt; parameterServerCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (pythonScriptFilePath As String, masterCommandLineArgs As String, Optional pythonInterpreterPath As String = null, Optional workerCommandLineArgs As String = null, Optional parameterServerCommandLineArgs As String = null, Optional workerCount As Nullable(Of Integer) = null, Optional parameterServerCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings : string * string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings (pythonScriptFilePath, masterCommandLineArgs, pythonInterpreterPath, workerCommandLineArgs, parameterServerCommandLineArgs, workerCount, parameterServerCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pythonScriptFilePath" Type="System.String" />
        <Parameter Name="masterCommandLineArgs" Type="System.String" />
        <Parameter Name="pythonInterpreterPath" Type="System.String" />
        <Parameter Name="workerCommandLineArgs" Type="System.String" />
        <Parameter Name="parameterServerCommandLineArgs" Type="System.String" />
        <Parameter Name="workerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="parameterServerCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="pythonScriptFilePath"><span data-ttu-id="07665-103">Der Pfad und Dateiname der Name des Python-Skript zum Ausführen des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="07665-103">The path and file name of the python script to execute the job.</span></span></param>
        <param name="masterCommandLineArgs"><span data-ttu-id="07665-104">Gibt die Befehlszeilenargumente für die master-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="07665-104">Specifies the command line arguments for the master task.</span></span></param>
        <param name="pythonInterpreterPath"><span data-ttu-id="07665-105">Der Pfad zur Python-Interpreter.</span><span class="sxs-lookup"><span data-stu-id="07665-105">The path to python interpreter.</span></span></param>
        <param name="workerCommandLineArgs"><span data-ttu-id="07665-106">Gibt die Befehlszeilenargumente für den Worker-Vorgang an.</span><span class="sxs-lookup"><span data-stu-id="07665-106">Specifies the command line arguments for the worker task.</span></span></param>
        <param name="parameterServerCommandLineArgs"><span data-ttu-id="07665-107">Gibt die Befehlszeilenargumente für den Parameter-Server-Task.</span><span class="sxs-lookup"><span data-stu-id="07665-107">Specifies the command line arguments for the parameter server task.</span></span></param>
        <param name="workerCount"><span data-ttu-id="07665-108">Die Anzahl der Worker-Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="07665-108">The number of worker tasks.</span></span></param>
        <param name="parameterServerCount"><span data-ttu-id="07665-109">Die Anzahl der-Parameters Server-Tasks.</span><span class="sxs-lookup"><span data-stu-id="07665-109">The number of parmeter server tasks.</span></span></param>
        <summary>
            <span data-ttu-id="07665-110">Initialisiert eine neue Instanz der TensorFlowSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07665-110">Initializes a new instance of the TensorFlowSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MasterCommandLineArgs">
      <MemberSignature Language="C#" Value="public string MasterCommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MasterCommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.MasterCommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property MasterCommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.MasterCommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.MasterCommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="masterCommandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07665-111">Ruft ab oder legt gibt die Befehlszeilenargumente für die master-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="07665-111">Gets or sets specifies the command line arguments for the master task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParameterServerCommandLineArgs">
      <MemberSignature Language="C#" Value="public string ParameterServerCommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ParameterServerCommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property ParameterServerCommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.ParameterServerCommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameterServerCommandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07665-112">Ruft ab oder legt gibt die Befehlszeilenargumente für den Parameter-Server-Task.</span><span class="sxs-lookup"><span data-stu-id="07665-112">Gets or sets specifies the command line arguments for the parameter server task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="07665-113">Diese Eigenschaft ist optional für das Training der einzelnen Computer.</span><span class="sxs-lookup"><span data-stu-id="07665-113">This property is optional for single machine training.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParameterServerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ParameterServerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ParameterServerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ParameterServerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ParameterServerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameterServerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07665-114">Ruft ab oder legt die Anzahl der-Parameters Servertasks.</span><span class="sxs-lookup"><span data-stu-id="07665-114">Gets or sets the number of parmeter server tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="07665-115">Wenn angegeben, muss der Wert kleiner als oder gleich angegeben sind.</span><span class="sxs-lookup"><span data-stu-id="07665-115">If specified, the value must be less than or equal to nodeCount.</span></span> <span data-ttu-id="07665-116">Wenn nicht angegeben, ist der Standardwert gleich 1 für verteilte TensorFlow Training (diese Eigenschaft gilt nicht für das Training einzelner Computer).</span><span class="sxs-lookup"><span data-stu-id="07665-116">If not specified, the default value is equal to 1 for distributed TensorFlow training (This property is not applicable for single machine training).</span></span> <span data-ttu-id="07665-117">Diese Eigenschaft kann nur für verteilte TensorFlow Training angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="07665-117">This property can be specified only for distributed TensorFlow training.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonInterpreterPath">
      <MemberSignature Language="C#" Value="public string PythonInterpreterPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonInterpreterPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonInterpreterPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonInterpreterPath As String" />
      <MemberSignature Language="F#" Value="member this.PythonInterpreterPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonInterpreterPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pythonInterpreterPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07665-118">Ruft ab oder legt den Pfad zu den Python-Interpreter fest.</span><span class="sxs-lookup"><span data-stu-id="07665-118">Gets or sets the path to python interpreter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonScriptFilePath">
      <MemberSignature Language="C#" Value="public string PythonScriptFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonScriptFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonScriptFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonScriptFilePath As String" />
      <MemberSignature Language="F#" Value="member this.PythonScriptFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonScriptFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pythonScriptFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07665-119">Ruft ab oder legt den Pfad und den Namen der Python-Skript zum Ausführen des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="07665-119">Gets or sets the path and file name of the python script to execute the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="tensorFlowSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07665-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="07665-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07665-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="07665-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WorkerCommandLineArgs">
      <MemberSignature Language="C#" Value="public string WorkerCommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerCommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.WorkerCommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerCommandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07665-122">Ruft ab oder legt gibt die Befehlszeilenargumente für den Worker-Vorgang an.</span><span class="sxs-lookup"><span data-stu-id="07665-122">Gets or sets specifies the command line arguments for the worker task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="07665-123">Diese Eigenschaft ist optional für das Training der einzelnen Computer.</span><span class="sxs-lookup"><span data-stu-id="07665-123">This property is optional for single machine training.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07665-124">Ruft ab oder legt die Anzahl der Worker-Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="07665-124">Gets or sets the number of worker tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="07665-125">Wenn angegeben, der Wert muss kleiner als oder gleich (NodeCount \* NumberOfGPUs pro virtueller Maschine).</span><span class="sxs-lookup"><span data-stu-id="07665-125">If specified, the value must be less than or equal to (nodeCount \* numberOfGPUs per VM).</span></span> <span data-ttu-id="07665-126">Wenn nicht angegeben, entspricht der Standardwert angegeben sind.</span><span class="sxs-lookup"><span data-stu-id="07665-126">If not specified, the default value is equal to nodeCount.</span></span> <span data-ttu-id="07665-127">Diese Eigenschaft kann nur für verteilte TensorFlow Training angegeben werden</span><span class="sxs-lookup"><span data-stu-id="07665-127">This property can be specified only for distributed TensorFlow training</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>