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
            Enthält Informationen zu öffentlichen SSH-Schlüssel und den Pfad für die Linux-VM, auf dem der öffentliche Schlüssel platziert wird.
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
            Initialisiert eine neue Instanz der SshPublicKey-Klasse.
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
        <param name="path">Gibt den vollständigen Pfad für die erstellten virtuellen Computer, auf dem SSH-öffentliche Schlüssel gespeichert ist. Wenn die Datei bereits vorhanden ist, wird der angegebene Schlüssel in der Datei angefügt. Beispiel: /home/user/.ssh/authorized_keys</param>
        <param name="keyData">SSH-Zertifikat für öffentliche Schlüssel mit dem virtuellen Computer über SSH-Authentifizierung verwendet. Der Schlüssel muss mindestens 2048-Bit- und ssh-Rsa-Format sein. &lt;Brasilien&gt;&lt;Br&gt; zum Erstellen von SSH-Schlüsseln, finden Sie unter [erstellen SSH-Schlüssel für Linux und Macintosh für virtuelle Linux-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-mac-create-ssh-keys?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</param>
        <summary>
            Initialisiert eine neue Instanz der SshPublicKey-Klasse.
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
            Ruft ab, oder legt ihn fest SSH-Zertifikat für öffentliche Schlüssels mit dem virtuellen Computer über SSH-Authentifizierung verwendet. Der Schlüssel muss mindestens 2048-Bit- und ssh-Rsa-Format sein. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Erstellen SSH-Schlüssel, finden Sie unter [erstellen SSH-Schlüssel für Linux und Macintosh für virtuelle Linux-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-mac-create-ssh-keys?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).
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
            Ruft ab oder legt gibt den vollständigen Pfad für die erstellten virtuellen Computer, auf dem SSH-öffentliche Schlüssel gespeichert ist. Wenn die Datei bereits vorhanden ist, wird der angegebene Schlüssel in der Datei angefügt. Beispiel: /home/user/.ssh/authorized_keys
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>