<Type Name="LinuxUserConfiguration" FullName="Microsoft.Azure.Batch.LinuxUserConfiguration">
  <TypeSignature Language="C#" Value="public class LinuxUserConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinuxUserConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.LinuxUserConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class LinuxUserConfiguration" />
  <TypeSignature Language="F#" Value="type LinuxUserConfiguration = class&#xA;    interface ITransportObjectProvider&lt;LinuxUserConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5fcca-101">Eigenschaften, die zum Erstellen eines Benutzerkontos auf einem Linux-Knoten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="5fcca-101">Properties used to create a user account on a Linux node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxUserConfiguration (Nullable&lt;int&gt; uid = null, Nullable&lt;int&gt; gid = null, string sshPrivateKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; uid, valuetype System.Nullable`1&lt;int32&gt; gid, string sshPrivateKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.LinuxUserConfiguration.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional uid As Nullable(Of Integer) = null, Optional gid As Nullable(Of Integer) = null, Optional sshPrivateKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.LinuxUserConfiguration : Nullable&lt;int&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Batch.LinuxUserConfiguration" Usage="new Microsoft.Azure.Batch.LinuxUserConfiguration (uid, gid, sshPrivateKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="uid" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="gid" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sshPrivateKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="uid"><span data-ttu-id="5fcca-102">Die Benutzer-ID des Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="5fcca-102">The user ID of the user account.</span></span></param>
        <param name="gid"><span data-ttu-id="5fcca-103">Die ID des Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="5fcca-103">The group ID of the user account.</span></span></param>
        <param name="sshPrivateKey"><span data-ttu-id="5fcca-104">Der private SSH-Schlüssel für das Benutzerkonto.</span><span class="sxs-lookup"><span data-stu-id="5fcca-104">The SSH private key for the user account.</span></span></param>
        <summary>
            <span data-ttu-id="5fcca-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.LinuxUserConfiguration" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5fcca-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.LinuxUserConfiguration" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Gid">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Gid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Gid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Gid" />
      <MemberSignature Language="VB.NET" Value="Public Property Gid As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Gid : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.LinuxUserConfiguration.Gid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fcca-106">Ruft ab oder legt die Gruppen-ID des Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="5fcca-106">Gets or sets the group ID of the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="5fcca-107">Die <see cref="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Uid" /> und <see cref="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Gid" /> Eigenschaften müssen zusammen oder überhaupt nicht angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="5fcca-107">The <see cref="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Uid" /> and <see cref="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Gid" /> properties must be specified together or not at all.</span></span> <span data-ttu-id="5fcca-108">Wenn nicht angegeben, wählt das zugrunde liegende Betriebssystem die Gid an.</span><span class="sxs-lookup"><span data-stu-id="5fcca-108">If not specified, the underlying operating system picks the gid.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPrivateKey">
      <MemberSignature Language="C#" Value="public string SshPrivateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPrivateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.LinuxUserConfiguration.SshPrivateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPrivateKey As String" />
      <MemberSignature Language="F#" Value="member this.SshPrivateKey : string with get, set" Usage="Microsoft.Azure.Batch.LinuxUserConfiguration.SshPrivateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fcca-109">Ruft ab oder legt den privaten SSH-Schlüssel für das Benutzerkonto.</span><span class="sxs-lookup"><span data-stu-id="5fcca-109">Gets or sets the SSH private key for the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="5fcca-110">Der private Schlüssel muss nicht kennwortgeschützt sein.</span><span class="sxs-lookup"><span data-stu-id="5fcca-110">The private key must not be password protected.</span></span> <span data-ttu-id="5fcca-111">Der private Schlüssel wird verwendet, so konfigurieren Sie die zertifikatbasierte Authentifizierung für SSH asymmetrischen Schlüssel zwischen Knoten in einer Linux automatisch Pools, wenn des Pools <see cref="P:Microsoft.Azure.Batch.CloudPool.InterComputeNodeCommunicationEnabled" /> Eigenschaft ist "true" (wird ignoriert, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.InterComputeNodeCommunicationEnabled" /> lautet "false").</span><span class="sxs-lookup"><span data-stu-id="5fcca-111">The private key is used to automatically configure asymmetric-key based authentication for SSH between nodes in a Linux pool when the pool's <see cref="P:Microsoft.Azure.Batch.CloudPool.InterComputeNodeCommunicationEnabled" /> property is true (it is ignored if <see cref="P:Microsoft.Azure.Batch.CloudPool.InterComputeNodeCommunicationEnabled" /> is false).</span></span> <span data-ttu-id="5fcca-112">Dies geschieht durch das Schlüsselpaar in das Verzeichnis des Benutzers .ssh platzieren.</span><span class="sxs-lookup"><span data-stu-id="5fcca-112">It does this by placing the key pair into the user's .ssh directory.</span></span> <span data-ttu-id="5fcca-113">Wenn nicht angegeben wird, kennwortlosen SSH ist nicht konfiguriert, zwischen Knoten (keine Änderung des .ssh-Verzeichnis des Benutzers erfolgt)</span><span class="sxs-lookup"><span data-stu-id="5fcca-113">If not specified, password-less SSH is not configured between nodes (no modification of the user's .ssh directory is done)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Uid">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Uid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Uid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Uid" />
      <MemberSignature Language="VB.NET" Value="Public Property Uid As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Uid : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.LinuxUserConfiguration.Uid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fcca-114">Ruft ab oder legt die Benutzer-ID des Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="5fcca-114">Gets or sets the user ID of the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="5fcca-115">Die <see cref="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Uid" /> und <see cref="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Gid" /> Eigenschaften müssen zusammen oder überhaupt nicht angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="5fcca-115">The <see cref="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Uid" /> and <see cref="P:Microsoft.Azure.Batch.LinuxUserConfiguration.Gid" /> properties must be specified together or not at all.</span></span> <span data-ttu-id="5fcca-116">Wenn nicht angegeben, wählt das zugrunde liegende Betriebssystem die Uid.</span><span class="sxs-lookup"><span data-stu-id="5fcca-116">If not specified, the underlying operating system picks the uid.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>