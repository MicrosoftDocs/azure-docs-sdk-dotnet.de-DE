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
            Der Satz von Änderungen an einem Benutzerkonto auf einem Knoten vorgenommen werden.
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
            Initialisiert eine neue Instanz der NodeUpdateUserParameter-Klasse.
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
        <param name="password">Das Kennwort des Kontos.</param>
        <param name="expiryTime">Der Zeitpunkt, an dem das Konto ablaufen sollen.</param>
        <param name="sshPublicKey">Der öffentliche SSH-Schlüssel, der für die Remoteanmeldung auf den Serverknoten verwendet werden kann.</param>
        <summary>
            Initialisiert eine neue Instanz der NodeUpdateUserParameter-Klasse.
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
            Ruft ab oder legt die Zeit, an der das Konto ablaufen sollen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, ist die Standardeinstellung 1 Tag nach der aktuellen Uhrzeit. Für Linux-Serverknoten hat die ExpiryTime eine Genauigkeit bis zu einem Tag.
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
            Ruft ab oder legt das Kennwort des Kontos.
            </summary>
        <value>To be added.</value>
        <remarks>
            Das Kennwort ist erforderlich für Windows-Knoten (die mit "CloudServiceConfiguration" erstellt oder mit "VirtualMachineConfiguration" mit einem Windows-Image-Verweis erstellt). Für Linux-Serverknoten kann das Kennwort optional zusammen mit der SshPublicKey-Eigenschaft angegeben werden. Wenn nicht angegeben, wird jeder vorhandenes Kennwort entfernt.
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
            Ruft ab oder legt den öffentlichen SSH-Schlüssel, der für die Remoteanmeldung auf den Serverknoten verwendet werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der öffentliche Schlüssel muss kompatibel mit OpenSSH Codierung und base-64 codiert werden soll. Diese Eigenschaft kann nur für Linux-Knoten angegeben werden. Wenn dies für einen Windows-Knoten angegeben wird, lehnt der Batch-Dienst die Anforderung ab; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung). Wenn nicht angegeben, wird jeder vorhandener Öffentlicher SSH-Schlüssel entfernt.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>