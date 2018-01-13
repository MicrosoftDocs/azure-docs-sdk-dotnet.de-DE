<Type Name="SshPublicKey" FullName="Microsoft.Azure.Management.Compute.Models.SshPublicKey">
  <TypeSignature Language="C#" Value="public class SshPublicKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SshPublicKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.SshPublicKey" />
  <TypeSignature Language="VB.NET" Value="Public Class SshPublicKey" />
  <TypeSignature Language="F#" Value="type SshPublicKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d23e9-101">Enthält Informationen zu öffentlichen SSH-Schlüssel und den Pfad für die Linux-VM, auf dem der öffentliche Schlüssel platziert wird.</span><span class="sxs-lookup"><span data-stu-id="d23e9-101">Contains information about SSH certificate public key and the path on the Linux VM where the public key is placed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SshPublicKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.SshPublicKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d23e9-102">Initialisiert eine neue Instanz der SshPublicKey-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d23e9-102">Initializes a new instance of the SshPublicKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SshPublicKey (string path = null, string keyData = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path, string keyData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.SshPublicKey.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional path As String = null, Optional keyData As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.SshPublicKey : string * string -&gt; Microsoft.Azure.Management.Compute.Models.SshPublicKey" Usage="new Microsoft.Azure.Management.Compute.Models.SshPublicKey (path, keyData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="keyData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="d23e9-103">Gibt den vollständigen Pfad für die erstellten virtuellen Computer, auf dem SSH-öffentliche Schlüssel gespeichert ist.</span><span class="sxs-lookup"><span data-stu-id="d23e9-103">Specifies the full path on the created VM where ssh public key is stored.</span></span> <span data-ttu-id="d23e9-104">Wenn die Datei bereits vorhanden ist, wird der angegebene Schlüssel in der Datei angefügt.</span><span class="sxs-lookup"><span data-stu-id="d23e9-104">If the file already exists, the specified key is appended to the file.</span></span> <span data-ttu-id="d23e9-105">Beispiel: /home/user/.ssh/authorized_keys</span><span class="sxs-lookup"><span data-stu-id="d23e9-105">Example: /home/user/.ssh/authorized_keys</span></span></param>
        <param name="keyData"><span data-ttu-id="d23e9-106">SSH-Zertifikat für öffentliche Schlüssel mit dem virtuellen Computer über SSH-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="d23e9-106">SSH public key certificate used to authenticate with the VM through ssh.</span></span> <span data-ttu-id="d23e9-107">Der Schlüssel muss mindestens 2048-Bit- und ssh-Rsa-Format sein.</span><span class="sxs-lookup"><span data-stu-id="d23e9-107">The key needs to be at least 2048-bit and in ssh-rsa format.</span></span> <span data-ttu-id="d23e9-108">&lt;Brasilien&gt;&lt;Br&gt; zum Erstellen von SSH-Schlüsseln, finden Sie unter [erstellen SSH-Schlüssel für Linux und Macintosh für virtuelle Linux-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-mac-create-ssh-keys?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="d23e9-108">&lt;br&gt;&lt;br&gt; For creating ssh keys, see [Create SSH keys on Linux and Mac for Linux VMs in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-mac-create-ssh-keys?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span></span></param>
        <summary>
            <span data-ttu-id="d23e9-109">Initialisiert eine neue Instanz der SshPublicKey-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d23e9-109">Initializes a new instance of the SshPublicKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyData">
      <MemberSignature Language="C#" Value="public string KeyData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.SshPublicKey.KeyData" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyData As String" />
      <MemberSignature Language="F#" Value="member this.KeyData : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.SshPublicKey.KeyData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d23e9-110">Ruft ab, oder legt ihn fest SSH-Zertifikat für öffentliche Schlüssels mit dem virtuellen Computer über SSH-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="d23e9-110">Gets or sets SSH public key certificate used to authenticate with the VM through ssh.</span></span> <span data-ttu-id="d23e9-111">Der Schlüssel muss mindestens 2048-Bit- und ssh-Rsa-Format sein.</span><span class="sxs-lookup"><span data-stu-id="d23e9-111">The key needs to be at least 2048-bit and in ssh-rsa format.</span></span> <span data-ttu-id="d23e9-112">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Erstellen SSH-Schlüssel, finden Sie unter [erstellen SSH-Schlüssel für Linux und Macintosh für virtuelle Linux-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-mac-create-ssh-keys?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="d23e9-112">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For creating ssh keys, see [Create SSH keys on Linux and Mac for Linux VMs in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-mac-create-ssh-keys?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.SshPublicKey.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.SshPublicKey.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d23e9-113">Ruft ab oder legt gibt den vollständigen Pfad für die erstellten virtuellen Computer, auf dem SSH-öffentliche Schlüssel gespeichert ist.</span><span class="sxs-lookup"><span data-stu-id="d23e9-113">Gets or sets specifies the full path on the created VM where ssh public key is stored.</span></span> <span data-ttu-id="d23e9-114">Wenn die Datei bereits vorhanden ist, wird der angegebene Schlüssel in der Datei angefügt.</span><span class="sxs-lookup"><span data-stu-id="d23e9-114">If the file already exists, the specified key is appended to the file.</span></span> <span data-ttu-id="d23e9-115">Beispiel: /home/user/.ssh/authorized_keys</span><span class="sxs-lookup"><span data-stu-id="d23e9-115">Example: /home/user/.ssh/authorized_keys</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>