<Type Name="BuildJobParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters">
  <TypeSignature Language="C#" Value="public class BuildJobParameters : Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BuildJobParameters extends Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class BuildJobParameters&#xA;Inherits BaseJobParameters" />
  <TypeSignature Language="F#" Value="type BuildJobParameters = class&#xA;    inherit BaseJobParameters" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d0b5-101">Die Parameter verwendet, um einen neuen Data Lake Analytics-Auftrag zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4d0b5-101">The parameters used to build a new Data Lake Analytics job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BuildJobParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d0b5-102">Initialisiert eine neue Instanz der BuildJobParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4d0b5-102">Initializes a new instance of the BuildJobParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BuildJobParameters (Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.#ctor(Microsoft.Azure.Management.DataLake.Analytics.Models.JobType,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As JobType, properties As CreateJobProperties, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters : Microsoft.Azure.Management.DataLake.Analytics.Models.JobType * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters (type, properties, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobType" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="4d0b5-103">Der Auftragstyp des aktuellen Auftrags (Hive oder USql).</span><span class="sxs-lookup"><span data-stu-id="4d0b5-103">the job type of the current job (Hive or USql).</span></span>
            <span data-ttu-id="4d0b5-104">Folgende Werte sind möglich: "USql", "Struktur"</span><span class="sxs-lookup"><span data-stu-id="4d0b5-104">Possible values include: 'USql', 'Hive'</span></span></param>
        <param name="properties"><span data-ttu-id="4d0b5-105">die spezifischen Eigenschaften des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="4d0b5-105">the job specific properties.</span></span></param>
        <param name="name"><span data-ttu-id="4d0b5-106">der angezeigte Name des Auftrags, zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4d0b5-106">the friendly name of the job to build.</span></span></param>
        <summary>
            <span data-ttu-id="4d0b5-107">Initialisiert eine neue Instanz der BuildJobParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4d0b5-107">Initializes a new instance of the BuildJobParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d0b5-108">Ruft ab oder legt den Anzeigenamen des Auftrags, zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4d0b5-108">Gets or sets the friendly name of the job to build.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="buildJobParameters.Validate " />
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
            <span data-ttu-id="4d0b5-109">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="4d0b5-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d0b5-110">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="4d0b5-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>