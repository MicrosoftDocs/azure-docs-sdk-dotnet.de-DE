<Type Name="SasDefinitionBundle" FullName="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle">
  <TypeSignature Language="C#" Value="public class SasDefinitionBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SasDefinitionBundle extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class SasDefinitionBundle" />
  <TypeSignature Language="F#" Value="type SasDefinitionBundle = class" />
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
            Ein SAS-Definition Paket besteht aus schlüsseltresor SAS-Definition Details sowie seiner Attribute.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SasDefinitionBundle-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionBundle (string id = null, string secretId = null, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string secretId, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.#ctor(System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional secretId As String = null, Optional parameters As IDictionary(Of String, String) = null, Optional attributes As SasDefinitionAttributes = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.SasDefinitionBundle : string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.SasDefinitionBundle" Usage="new Microsoft.Azure.KeyVault.Models.SasDefinitionBundle (id, secretId, parameters, attributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="secretId" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Die Id des SAS-Definition.</param>
        <param name="secretId">Speicher-Konto-SAS-Definition für den geheimen-ID.</param>
        <param name="parameters">Die SAS-Definition Metadaten in Form von Schlüssel-Wert-Paaren.</param>
        <param name="attributes">Die Attribute für den SAS-Definition.</param>
        <param name="tags">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren</param>
        <summary>
            Initialisiert eine neue Instanz der SasDefinitionBundle-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes Attributes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Attributes As SasDefinitionAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Attributes" />
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
            Ruft die Attribute der SAS-Definition ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Id" />
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
            Ruft die Id des SAS-Definition.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Metadaten der SAS-Definition in Form von Schlüssel-Wert-Paaren ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretId">
      <MemberSignature Language="C#" Value="public string SecretId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.SecretId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecretId As String" />
      <MemberSignature Language="F#" Value="member this.SecretId : string" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.SecretId" />
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
            Ruft Storage-Konto-SAS-Definition für den geheimen Id ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Tags" />
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
            Ruft die Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>