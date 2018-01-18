<Type Name="LinuxUserConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration">
  <TypeSignature Language="C#" Value="public class LinuxUserConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinuxUserConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class LinuxUserConfiguration" />
  <TypeSignature Language="F#" Value="type LinuxUserConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="422dc-101">Eigenschaften, die zum Erstellen eines Benutzerkontos auf einem Linux-Knoten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="422dc-101">Properties used to create a user account on a Linux node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxUserConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="422dc-102">Initialisiert eine neue Instanz der LinuxUserConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="422dc-102">Initializes a new instance of the LinuxUserConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxUserConfiguration (Nullable&lt;int&gt; uid = null, Nullable&lt;int&gt; gid = null, string sshPrivateKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; uid, valuetype System.Nullable`1&lt;int32&gt; gid, string sshPrivateKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional uid As Nullable(Of Integer) = null, Optional gid As Nullable(Of Integer) = null, Optional sshPrivateKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration : Nullable&lt;int&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration (uid, gid, sshPrivateKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="uid" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="gid" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sshPrivateKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="uid"><span data-ttu-id="422dc-103">Die Benutzer-ID des Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="422dc-103">The user ID of the user account.</span></span></param>
        <param name="gid"><span data-ttu-id="422dc-104">Die ID für das Benutzerkonto an.</span><span class="sxs-lookup"><span data-stu-id="422dc-104">The group ID for the user account.</span></span></param>
        <param name="sshPrivateKey"><span data-ttu-id="422dc-105">Der private SSH-Schlüssel für das Benutzerkonto.</span><span class="sxs-lookup"><span data-stu-id="422dc-105">The SSH private key for the user account.</span></span></param>
        <summary>
            <span data-ttu-id="422dc-106">Initialisiert eine neue Instanz der LinuxUserConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="422dc-106">Initializes a new instance of the LinuxUserConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Gid">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Gid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Gid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.Gid" />
      <MemberSignature Language="VB.NET" Value="Public Property Gid As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Gid : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.Gid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="gid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="422dc-107">Ruft ab oder legt die Gruppen-ID für das Benutzerkonto an.</span><span class="sxs-lookup"><span data-stu-id="422dc-107">Gets or sets the group ID for the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="422dc-108">Die Uid und Gid-Eigenschaft müssen zusammen oder überhaupt nicht angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="422dc-108">The uid and gid properties must be specified together or not at all.</span></span> <span data-ttu-id="422dc-109">Wenn nicht angegeben des zugrunde liegenden Betriebssystems wählt System die Gid an.</span><span class="sxs-lookup"><span data-stu-id="422dc-109">If not specified the underlying operating system picks the gid.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPrivateKey">
      <MemberSignature Language="C#" Value="public string SshPrivateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPrivateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.SshPrivateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPrivateKey As String" />
      <MemberSignature Language="F#" Value="member this.SshPrivateKey : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.SshPrivateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sshPrivateKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="422dc-110">Ruft ab oder legt den privaten SSH-Schlüssel für das Benutzerkonto.</span><span class="sxs-lookup"><span data-stu-id="422dc-110">Gets or sets the SSH private key for the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="422dc-111">Der private Schlüssel muss nicht kennwortgeschützt sein.</span><span class="sxs-lookup"><span data-stu-id="422dc-111">The private key must not be password protected.</span></span> <span data-ttu-id="422dc-112">Der private Schlüssel wird verwendet, um asymmetrische Schlüssel zertifikatbasierte Authentifizierung für SSH zwischen Knoten in einem Linux-Pool, wenn der Pool EnableInterNodeCommunication-Eigenschaft true ist (es wird ignoriert, wenn EnableInterNodeCommunication auf "false" festgelegt ist) automatisch zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="422dc-112">The private key is used to automatically configure asymmetric-key based authentication for SSH between nodes in a Linux pool when the pool's enableInterNodeCommunication property is true (it is ignored if enableInterNodeCommunication is false).</span></span> <span data-ttu-id="422dc-113">Dies geschieht durch das Schlüsselpaar in das Verzeichnis des Benutzers .ssh platzieren.</span><span class="sxs-lookup"><span data-stu-id="422dc-113">It does this by placing the key pair into the user's .ssh directory.</span></span> <span data-ttu-id="422dc-114">Wenn dies nicht angegeben wird, kennwortlosen SSH nicht zwischen Knoten (keine Änderung des .ssh-Verzeichnis des Benutzers erfolgt) konfiguriert ist.</span><span class="sxs-lookup"><span data-stu-id="422dc-114">If not specified, password-less SSH is not configured between nodes (no modification of the user's .ssh directory is done).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Uid">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Uid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Uid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.Uid" />
      <MemberSignature Language="VB.NET" Value="Public Property Uid As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Uid : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.Uid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="422dc-115">Ruft ab oder legt die Benutzer-ID des Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="422dc-115">Gets or sets the user ID of the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="422dc-116">Die Uid und Gid-Eigenschaft müssen zusammen oder überhaupt nicht angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="422dc-116">The uid and gid properties must be specified together or not at all.</span></span> <span data-ttu-id="422dc-117">Wenn nicht angegeben des zugrunde liegenden Betriebssystems wählt System die Uid.</span><span class="sxs-lookup"><span data-stu-id="422dc-117">If not specified the underlying operating system picks the uid.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>