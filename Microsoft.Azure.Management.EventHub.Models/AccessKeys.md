<Type Name="AccessKeys" FullName="Microsoft.Azure.Management.EventHub.Models.AccessKeys">
  <TypeSignature Language="C#" Value="public class AccessKeys" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccessKeys extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.Models.AccessKeys" />
  <TypeSignature Language="VB.NET" Value="Public Class AccessKeys" />
  <TypeSignature Language="F#" Value="type AccessKeys = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Namespace/EventHub-Verbindungszeichenfolge
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.AccessKeys.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AccessKeys-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessKeys (string primaryConnectionString = null, string secondaryConnectionString = null, string aliasPrimaryConnectionString = null, string aliasSecondaryConnectionString = null, string primaryKey = null, string secondaryKey = null, string keyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primaryConnectionString, string secondaryConnectionString, string aliasPrimaryConnectionString, string aliasSecondaryConnectionString, string primaryKey, string secondaryKey, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.AccessKeys.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primaryConnectionString As String = null, Optional secondaryConnectionString As String = null, Optional aliasPrimaryConnectionString As String = null, Optional aliasSecondaryConnectionString As String = null, Optional primaryKey As String = null, Optional secondaryKey As String = null, Optional keyName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventHub.Models.AccessKeys : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.AccessKeys" Usage="new Microsoft.Azure.Management.EventHub.Models.AccessKeys (primaryConnectionString, secondaryConnectionString, aliasPrimaryConnectionString, aliasSecondaryConnectionString, primaryKey, secondaryKey, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryConnectionString" Type="System.String" />
        <Parameter Name="secondaryConnectionString" Type="System.String" />
        <Parameter Name="aliasPrimaryConnectionString" Type="System.String" />
        <Parameter Name="aliasSecondaryConnectionString" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primaryConnectionString">Primäre Verbindungszeichenfolge für den erstellten Namespace AuthorizationRule.</param>
        <param name="secondaryConnectionString">Sekundäre Verbindungszeichenfolge für den erstellten Namespace AuthorizationRule.</param>
        <param name="aliasPrimaryConnectionString">Primäre Verbindungszeichenfolge für den Alias, wenn GEO-DR aktiviert ist</param>
        <param name="aliasSecondaryConnectionString">Sekundäre Verbindungszeichenfolge für den Alias, wenn GEO-DR aktiviert ist</param>
        <param name="primaryKey">Ein primärer Base64-codierter 256-Bit-Schlüssel zum Signieren und Überprüfen des SAS-Tokens.</param>
        <param name="secondaryKey">Ein primärer Base64-codierter 256-Bit-Schlüssel zum Signieren und Überprüfen des SAS-Tokens.</param>
        <param name="keyName">Eine Zeichenfolge, die AuthorizationRule beschreibt.</param>
        <summary>
            Initialisiert eine neue Instanz der AccessKeys-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AliasPrimaryConnectionString">
      <MemberSignature Language="C#" Value="public string AliasPrimaryConnectionString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AliasPrimaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.AccessKeys.AliasPrimaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AliasPrimaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.AliasPrimaryConnectionString : string" Usage="Microsoft.Azure.Management.EventHub.Models.AccessKeys.AliasPrimaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aliasPrimaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die primäre Verbindungszeichenfolge des Alias ab, wenn GEO-DR aktiviert ist
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AliasSecondaryConnectionString">
      <MemberSignature Language="C#" Value="public string AliasSecondaryConnectionString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AliasSecondaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.AccessKeys.AliasSecondaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AliasSecondaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.AliasSecondaryConnectionString : string" Usage="Microsoft.Azure.Management.EventHub.Models.AccessKeys.AliasSecondaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aliasSecondaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die sekundäre Verbindungszeichenfolge des Alias ab, wenn GEO-DR aktiviert ist
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.AccessKeys.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string" Usage="Microsoft.Azure.Management.EventHub.Models.AccessKeys.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Zeichenfolge, die AuthorizationRule beschreibt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryConnectionString">
      <MemberSignature Language="C#" Value="public string PrimaryConnectionString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.AccessKeys.PrimaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryConnectionString : string" Usage="Microsoft.Azure.Management.EventHub.Models.AccessKeys.PrimaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die primäre Verbindungszeichenfolge für den erstellten Namespace AuthorizationRule ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.AccessKeys.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string" Usage="Microsoft.Azure.Management.EventHub.Models.AccessKeys.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen base64-codierte primären 256-Bit-Schlüssel zum Signieren und überprüfen das SAS-Token.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryConnectionString">
      <MemberSignature Language="C#" Value="public string SecondaryConnectionString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.AccessKeys.SecondaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryConnectionString : string" Usage="Microsoft.Azure.Management.EventHub.Models.AccessKeys.SecondaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die sekundäre Verbindungszeichenfolge für den erstellten Namespace AuthorizationRule ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.AccessKeys.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string" Usage="Microsoft.Azure.Management.EventHub.Models.AccessKeys.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen base64-codierte primären 256-Bit-Schlüssel zum Signieren und überprüfen das SAS-Token.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>