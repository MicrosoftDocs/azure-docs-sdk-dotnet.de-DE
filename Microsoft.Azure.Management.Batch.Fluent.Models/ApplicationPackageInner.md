<Type Name="ApplicationPackageInner" FullName="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner">
  <TypeSignature Language="C#" Value="public class ApplicationPackageInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationPackageInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationPackageInner" />
  <TypeSignature Language="F#" Value="type ApplicationPackageInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1091-101">Ein Anwendungspaket, das eine bestimmte Version einer Anwendung darstellt.</span><span class="sxs-lookup"><span data-stu-id="d1091-101">An application package which represents a particular version of an application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d1091-102">Initialisiert eine neue Instanz der ApplicationPackageInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1091-102">Initializes a new instance of the ApplicationPackageInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageInner (string id = null, string version = null, Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PackageState&gt; state = null, string format = null, string storageUrl = null, Nullable&lt;DateTime&gt; storageUrlExpiry = null, Nullable&lt;DateTime&gt; lastActivationTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string version, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Fluent.Models.PackageState&gt; state, string format, string storageUrl, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; storageUrlExpiry, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastActivationTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Batch.Fluent.Models.PackageState},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional version As String = null, Optional state As Nullable(Of PackageState) = null, Optional format As String = null, Optional storageUrl As String = null, Optional storageUrlExpiry As Nullable(Of DateTime) = null, Optional lastActivationTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner : string * string * Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PackageState&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner" Usage="new Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner (id, version, state, format, storageUrl, storageUrlExpiry, lastActivationTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PackageState&gt;" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="storageUrl" Type="System.String" />
        <Parameter Name="storageUrlExpiry" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastActivationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="d1091-103">Die ID der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="d1091-103">The ID of the application.</span></span></param>
        <param name="version"><span data-ttu-id="d1091-104">Die Version des Anwendungspakets.</span><span class="sxs-lookup"><span data-stu-id="d1091-104">The version of the application package.</span></span>
            </param>
        <param name="state"><span data-ttu-id="d1091-105">Der aktuelle Status des Anwendungspakets.</span><span class="sxs-lookup"><span data-stu-id="d1091-105">The current state of the application package.</span></span>
            <span data-ttu-id="d1091-106">Folgende Werte sind möglich: "Ausstehend", "aktiv", "Zuordnung"</span><span class="sxs-lookup"><span data-stu-id="d1091-106">Possible values include: 'pending', 'active', 'unmapped'</span></span></param>
        <param name="format"><span data-ttu-id="d1091-107">Das Format des Anwendungspakets, wenn das Paket aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="d1091-107">The format of the application package, if the package is active.</span></span></param>
        <param name="storageUrl"><span data-ttu-id="d1091-108">Die Speicher-URL, an dem das Anwendungspaket gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="d1091-108">The storage URL at which the application package is stored.</span></span></param>
        <param name="storageUrlExpiry"><span data-ttu-id="d1091-109">Die UTC-Zeit, zu der die Speicher-URL abläuft.</span><span class="sxs-lookup"><span data-stu-id="d1091-109">The UTC time at which the storage URL will expire.</span></span></param>
        <param name="lastActivationTime"><span data-ttu-id="d1091-110">Der Zeitpunkt, an dem das Paket zuletzt aktiviert war, wenn das Paket aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="d1091-110">The time at which the package was last activated, if the package is active.</span></span></param>
        <summary>
            <span data-ttu-id="d1091-111">Initialisiert eine neue Instanz der ApplicationPackageInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1091-111">Initializes a new instance of the ApplicationPackageInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public string Format { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.Format" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Format As String" />
      <MemberSignature Language="F#" Value="member this.Format : string" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1091-112">Ruft ab oder legt das Format des Anwendungspakets, wenn das Paket aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="d1091-112">Gets or sets the format of the application package, if the package is active.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1091-113">Ruft ab oder legt die ID der Anwendung fest.</span><span class="sxs-lookup"><span data-stu-id="d1091-113">Gets or sets the ID of the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastActivationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastActivationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastActivationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.LastActivationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastActivationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastActivationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.LastActivationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastActivationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1091-114">Ruft ab oder legt die Zeit, an der das Paket zuletzt aktiviert war, wenn das Paket aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="d1091-114">Gets or sets the time at which the package was last activated, if the package is active.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PackageState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Fluent.Models.PackageState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of PackageState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PackageState&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PackageState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1091-115">Ruft ab oder legt den aktuellen Status des Anwendungspakets.</span><span class="sxs-lookup"><span data-stu-id="d1091-115">Gets or sets the current state of the application package.</span></span> <span data-ttu-id="d1091-116">Folgende Werte sind möglich: "Ausstehend", "aktiv", "Zuordnung"</span><span class="sxs-lookup"><span data-stu-id="d1091-116">Possible values include: 'pending', 'active', 'unmapped'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUrl">
      <MemberSignature Language="C#" Value="public string StorageUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.StorageUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUrl As String" />
      <MemberSignature Language="F#" Value="member this.StorageUrl : string" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.StorageUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1091-117">Ruft ab oder legt die Speicher-URL, an dem das Anwendungspaket gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="d1091-117">Gets or sets the storage URL at which the application package is stored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUrlExpiry">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StorageUrlExpiry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StorageUrlExpiry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.StorageUrlExpiry" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUrlExpiry As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StorageUrlExpiry : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.StorageUrlExpiry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageUrlExpiry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1091-118">Ruft ab oder legt die UTC-Zeit, zu der die Speicher-URL abläuft.</span><span class="sxs-lookup"><span data-stu-id="d1091-118">Gets or sets the UTC time at which the storage URL will expire.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1091-119">Ruft ab oder legt die Version des Anwendungspakets.</span><span class="sxs-lookup"><span data-stu-id="d1091-119">Gets or sets the version of the application package.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>