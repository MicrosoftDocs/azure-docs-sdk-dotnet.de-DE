<Type Name="SasDefinitionItem" FullName="Microsoft.Azure.KeyVault.Models.SasDefinitionItem">
  <TypeSignature Language="C#" Value="public class SasDefinitionItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SasDefinitionItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.SasDefinitionItem" />
  <TypeSignature Language="VB.NET" Value="Public Class SasDefinitionItem" />
  <TypeSignature Language="F#" Value="type SasDefinitionItem = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Speicher-SAS-Definition Elementmetadaten mit Speicher-SAS-Definition.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SasDefinitionItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionItem (string id = null, string secretId = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string secretId, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.#ctor(System.String,System.String,Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional secretId As String = null, Optional attributes As SasDefinitionAttributes = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.SasDefinitionItem : string * string * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.SasDefinitionItem" Usage="new Microsoft.Azure.KeyVault.Models.SasDefinitionItem (id, secretId, attributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="secretId" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Der Bezeichner für den Speicher-SAS.</param>
        <param name="secretId">Die Speicher-Konto-SAS-Definition für den geheimen-ID.</param>
        <param name="attributes">Die SAS-Definition Management-Attribute.</param>
        <param name="tags">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</param>
        <summary>
            Initialisiert eine neue Instanz der SasDefinitionItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes Attributes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Attributes As SasDefinitionAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Attributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="attributes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Definition des SAS-Management-Attribute ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            Ruft den Speicher-SAS-Bezeichner ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.SasDefinitionIdentifier Identifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.SasDefinitionIdentifier Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Identifier As SasDefinitionIdentifier" />
      <MemberSignature Language="F#" Value="member this.Identifier : Microsoft.Azure.KeyVault.SasDefinitionIdentifier" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.SasDefinitionIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der schlüsseltresor Speicher SAS-Definition Bezeichner.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretId">
      <MemberSignature Language="C#" Value="public string SecretId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.SecretId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecretId As String" />
      <MemberSignature Language="F#" Value="member this.SecretId : string" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.SecretId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Konto-SAS-Definition für den geheimen-Id ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>