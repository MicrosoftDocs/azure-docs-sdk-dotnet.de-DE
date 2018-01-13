<Type Name="Permissions" FullName="Microsoft.Azure.Management.KeyVault.Models.Permissions">
  <TypeSignature Language="C#" Value="public class Permissions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Permissions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Models.Permissions" />
  <TypeSignature Language="VB.NET" Value="Public Class Permissions" />
  <TypeSignature Language="F#" Value="type Permissions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Über Berechtigungen verfügt die Identität für den Schlüssel, geheime Schlüssel, Zertifikate und Speicher.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Permissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.Permissions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Berechtigungen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Permissions (System.Collections.Generic.IList&lt;string&gt; keys = null, System.Collections.Generic.IList&lt;string&gt; secrets = null, System.Collections.Generic.IList&lt;string&gt; certificates = null, System.Collections.Generic.IList&lt;string&gt; storage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; keys, class System.Collections.Generic.IList`1&lt;string&gt; secrets, class System.Collections.Generic.IList`1&lt;string&gt; certificates, class System.Collections.Generic.IList`1&lt;string&gt; storage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.Permissions.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keys As IList(Of String) = null, Optional secrets As IList(Of String) = null, Optional certificates As IList(Of String) = null, Optional storage As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Models.Permissions : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.KeyVault.Models.Permissions" Usage="new Microsoft.Azure.Management.KeyVault.Models.Permissions (keys, secrets, certificates, storage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keys" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="secrets" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="certificates" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="storage" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="keys">Berechtigungen für Schlüssel</param>
        <param name="secrets">Berechtigungen für geheime Schlüssel</param>
        <param name="certificates">Berechtigungen für Zertifikate</param>
        <param name="storage">Berechtigungen für Speicherkonten</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Berechtigungen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.Permissions.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificates As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Certificates : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.Permissions.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Berechtigungen von Zertifikaten
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Keys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.Permissions.Keys" />
      <MemberSignature Language="VB.NET" Value="Public Property Keys As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Keys : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.Permissions.Keys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Berechtigungen auf Schlüssel
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secrets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Secrets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Secrets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.Permissions.Secrets" />
      <MemberSignature Language="VB.NET" Value="Public Property Secrets As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Secrets : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.Permissions.Secrets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secrets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Berechtigungen auf geheime Schlüssel
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Storage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Storage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Storage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.Permissions.Storage" />
      <MemberSignature Language="VB.NET" Value="Public Property Storage As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Storage : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.Permissions.Storage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Berechtigungen in Speicherkonten
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>