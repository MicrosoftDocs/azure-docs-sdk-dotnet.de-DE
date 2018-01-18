<Type Name="CreateUSqlJobProperties" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties">
  <TypeSignature Language="C#" Value="public class CreateUSqlJobProperties : Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CreateUSqlJobProperties extends Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class CreateUSqlJobProperties&#xA;Inherits CreateJobProperties" />
  <TypeSignature Language="F#" Value="type CreateUSqlJobProperties = class&#xA;    inherit CreateJobProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("USql")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ba572-101">U-SQL-Auftragseigenschaften verwendet, wenn der U-SQL-Aufträge zu übermitteln.</span><span class="sxs-lookup"><span data-stu-id="ba572-101">U-SQL job properties used when submitting U-SQL jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreateUSqlJobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba572-102">Initialisiert eine neue Instanz der CreateUSqlJobProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ba572-102">Initializes a new instance of the CreateUSqlJobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreateUSqlJobProperties (string script, string runtimeVersion = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; compileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script, string runtimeVersion, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; compileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (script As String, Optional runtimeVersion As String = null, Optional compileMode As Nullable(Of CompileMode) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties : string * string * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties (script, runtimeVersion, compileMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
        <Parameter Name="runtimeVersion" Type="System.String" />
        <Parameter Name="compileMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt;" />
      </Parameters>
      <Docs>
        <param name="script"><span data-ttu-id="ba572-103">das auszuführende Skript</span><span class="sxs-lookup"><span data-stu-id="ba572-103">the script to run</span></span></param>
        <param name="runtimeVersion"><span data-ttu-id="ba572-104">die Common Language Runtime-Version des Data Lake Analytics-Moduls für den spezifischen Typ der ausgeführten Auftrags verwenden.</span><span class="sxs-lookup"><span data-stu-id="ba572-104">the runtime version of the Data Lake Analytics engine to use for the specific type of job being run.</span></span></param>
        <param name="compileMode"><span data-ttu-id="ba572-105">Optional erzwingt einen bestimmten Kompilierungsmodus für den Auftrag während der Ausführung.</span><span class="sxs-lookup"><span data-stu-id="ba572-105">Optionally enforces a specific compilation mode for the job during execution.</span></span> <span data-ttu-id="ba572-106">Wenn dies während der Übermittlung nicht angegeben ist, wird der Server die optimale Kompilierungsmodus bestimmen.</span><span class="sxs-lookup"><span data-stu-id="ba572-106">If this is not specified during submission, the server will determine the optimal compilation mode.</span></span> <span data-ttu-id="ba572-107">Folgende Werte sind möglich: 'Semantisch', 'Full', 'SingleBox'</span><span class="sxs-lookup"><span data-stu-id="ba572-107">Possible values include: 'Semantic', 'Full', 'SingleBox'</span></span></param>
        <summary>
            <span data-ttu-id="ba572-108">Initialisiert eine neue Instanz der CreateUSqlJobProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ba572-108">Initializes a new instance of the CreateUSqlJobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompileMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; CompileMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; CompileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties.CompileMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CompileMode As Nullable(Of CompileMode)" />
      <MemberSignature Language="F#" Value="member this.CompileMode : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties.CompileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="compileMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba572-109">Ruft ab oder legt ihn fest und erzwingt optional einen bestimmten Kompilierungsmodus für den Auftrag während der Ausführung ein.</span><span class="sxs-lookup"><span data-stu-id="ba572-109">Gets or sets optionally enforces a specific compilation mode for the job during execution.</span></span> <span data-ttu-id="ba572-110">Wenn dies während der Übermittlung nicht angegeben ist, wird der Server die optimale Kompilierungsmodus bestimmen.</span><span class="sxs-lookup"><span data-stu-id="ba572-110">If this is not specified during submission, the server will determine the optimal compilation mode.</span></span>
            <span data-ttu-id="ba572-111">Folgende Werte sind möglich: 'Semantisch', 'Full', 'SingleBox'</span><span class="sxs-lookup"><span data-stu-id="ba572-111">Possible values include: 'Semantic', 'Full', 'SingleBox'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateUSqlJobProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="createUSqlJobProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba572-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ba572-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ba572-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ba572-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>