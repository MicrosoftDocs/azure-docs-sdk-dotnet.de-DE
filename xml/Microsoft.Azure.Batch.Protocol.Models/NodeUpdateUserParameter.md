<Type Name="NodeUpdateUserParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter">
  <TypeSignature Language="C#" Value="public class NodeUpdateUserParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeUpdateUserParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeUpdateUserParameter" />
  <TypeSignature Language="F#" Value="type NodeUpdateUserParameter = class" />
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
            <span data-ttu-id="91b2f-101">Der Satz von Änderungen an einem Benutzerkonto auf einem Knoten vorgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="91b2f-101">The set of changes to be made to a user account on a node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeUpdateUserParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="91b2f-102">Initialisiert eine neue Instanz der NodeUpdateUserParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="91b2f-102">Initializes a new instance of the NodeUpdateUserParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeUpdateUserParameter (string password = null, Nullable&lt;DateTime&gt; expiryTime = null, string sshPublicKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string password, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiryTime, string sshPublicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.#ctor(System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional password As String = null, Optional expiryTime As Nullable(Of DateTime) = null, Optional sshPublicKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter : string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter (password, expiryTime, sshPublicKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="expiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="sshPublicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="password"><span data-ttu-id="91b2f-103">Das Kennwort des Kontos.</span><span class="sxs-lookup"><span data-stu-id="91b2f-103">The password of the account.</span></span></param>
        <param name="expiryTime"><span data-ttu-id="91b2f-104">Der Zeitpunkt, an dem das Konto ablaufen sollen.</span><span class="sxs-lookup"><span data-stu-id="91b2f-104">The time at which the account should expire.</span></span></param>
        <param name="sshPublicKey"><span data-ttu-id="91b2f-105">Der öffentliche SSH-Schlüssel, der für die Remoteanmeldung auf den Serverknoten verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="91b2f-105">The SSH public key that can be used for remote login to the compute node.</span></span></param>
        <summary>
            <span data-ttu-id="91b2f-106">Initialisiert eine neue Instanz der NodeUpdateUserParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="91b2f-106">Initializes a new instance of the NodeUpdateUserParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpiryTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.ExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expiryTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91b2f-107">Ruft ab oder legt die Zeit, an der das Konto ablaufen sollen.</span><span class="sxs-lookup"><span data-stu-id="91b2f-107">Gets or sets the time at which the account should expire.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91b2f-108">Wenn nicht angegeben, ist die Standardeinstellung 1 Tag nach der aktuellen Uhrzeit.</span><span class="sxs-lookup"><span data-stu-id="91b2f-108">If omitted, the default is 1 day from the current time.</span></span> <span data-ttu-id="91b2f-109">Für Linux-Serverknoten hat die ExpiryTime eine Genauigkeit bis zu einem Tag.</span><span class="sxs-lookup"><span data-stu-id="91b2f-109">For Linux compute nodes, the expiryTime has a precision up to a day.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91b2f-110">Ruft ab oder legt das Kennwort des Kontos.</span><span class="sxs-lookup"><span data-stu-id="91b2f-110">Gets or sets the password of the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91b2f-111">Das Kennwort ist erforderlich für Windows-Knoten (die mit "CloudServiceConfiguration" erstellt oder mit "VirtualMachineConfiguration" mit einem Windows-Image-Verweis erstellt).</span><span class="sxs-lookup"><span data-stu-id="91b2f-111">The password is required for Windows nodes (those created with 'cloudServiceConfiguration', or created with 'virtualMachineConfiguration' using a Windows image reference).</span></span> <span data-ttu-id="91b2f-112">Für Linux-Serverknoten kann das Kennwort optional zusammen mit der SshPublicKey-Eigenschaft angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="91b2f-112">For Linux compute nodes, the password can optionally be specified along with the sshPublicKey property.</span></span> <span data-ttu-id="91b2f-113">Wenn nicht angegeben, wird jeder vorhandenes Kennwort entfernt.</span><span class="sxs-lookup"><span data-stu-id="91b2f-113">If omitted, any existing password is removed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPublicKey">
      <MemberSignature Language="C#" Value="public string SshPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.SshPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.SshPublicKey : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.SshPublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sshPublicKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91b2f-114">Ruft ab oder legt den öffentlichen SSH-Schlüssel, der für die Remoteanmeldung auf den Serverknoten verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="91b2f-114">Gets or sets the SSH public key that can be used for remote login to the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91b2f-115">Der öffentliche Schlüssel muss kompatibel mit OpenSSH Codierung und base-64 codiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="91b2f-115">The public key should be compatible with OpenSSH encoding and should be base 64 encoded.</span></span> <span data-ttu-id="91b2f-116">Diese Eigenschaft kann nur für Linux-Knoten angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="91b2f-116">This property can be specified only for Linux nodes.</span></span> <span data-ttu-id="91b2f-117">Wenn dies für einen Windows-Knoten angegeben wird, lehnt der Batch-Dienst die Anforderung ab; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).</span><span class="sxs-lookup"><span data-stu-id="91b2f-117">If this is specified for a Windows node, then the Batch service rejects the request; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span> <span data-ttu-id="91b2f-118">Wenn nicht angegeben, wird jeder vorhandener Öffentlicher SSH-Schlüssel entfernt.</span><span class="sxs-lookup"><span data-stu-id="91b2f-118">If omitted, any existing SSH public key is removed.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>