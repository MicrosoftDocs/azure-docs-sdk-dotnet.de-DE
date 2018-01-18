<Type Name="JobProperties" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties">
  <TypeSignature Language="C#" Value="public class JobProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class JobProperties" />
  <TypeSignature Language="F#" Value="type JobProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9d038-101">Die allgemeinen Eigenschaften der Data Lake Analytics-Auftrag.</span><span class="sxs-lookup"><span data-stu-id="9d038-101">The common Data Lake Analytics job properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d038-102">Initialisiert eine neue Instanz der JobProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9d038-102">Initializes a new instance of the JobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobProperties (string script, string runtimeVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script, string runtimeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (script As String, Optional runtimeVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties : string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties (script, runtimeVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
        <Parameter Name="runtimeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="script"><span data-ttu-id="9d038-103">das auszuführende Skript</span><span class="sxs-lookup"><span data-stu-id="9d038-103">the script to run</span></span></param>
        <param name="runtimeVersion"><span data-ttu-id="9d038-104">die Common Language Runtime-Version des Data Lake Analytics-Moduls für den spezifischen Typ der ausgeführten Auftrags verwenden.</span><span class="sxs-lookup"><span data-stu-id="9d038-104">the runtime version of the Data Lake Analytics engine to use for the specific type of job being run.</span></span></param>
        <summary>
            <span data-ttu-id="9d038-105">Initialisiert eine neue Instanz der JobProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9d038-105">Initializes a new instance of the JobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public string RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As String" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runtimeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d038-106">Ruft ab oder legt die Common Language Runtime-Version des Data Lake Analytics-Moduls für den spezifischen Typ der ausgeführten Auftrags verwenden.</span><span class="sxs-lookup"><span data-stu-id="9d038-106">Gets or sets the runtime version of the Data Lake Analytics engine to use for the specific type of job being run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public string Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As String" />
      <MemberSignature Language="F#" Value="member this.Script : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties.Script" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="script")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d038-107">Ruft ab oder legt das auszuführende Skript</span><span class="sxs-lookup"><span data-stu-id="9d038-107">Gets or sets the script to run</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobProperties.Validate " />
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
            <span data-ttu-id="9d038-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9d038-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9d038-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9d038-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>