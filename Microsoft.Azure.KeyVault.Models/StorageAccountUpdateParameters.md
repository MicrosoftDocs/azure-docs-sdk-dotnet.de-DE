<Type Name="StorageAccountUpdateParameters" FullName="Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters">
  <TypeSignature Language="C#" Value="public class StorageAccountUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountUpdateParameters" />
  <TypeSignature Language="F#" Value="type StorageAccountUpdateParameters = class" />
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
            Die Speicher-Konto-Update-Parameter.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountUpdateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountUpdateParameters (string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.#ctor(System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters : string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters" Usage="new Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters (activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="activeKeyName">Der aktuellen aktiven Schlüssel speicherkontoname.</param>
        <param name="autoRegenerateKey">Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.</param>
        <param name="regenerationPeriod">Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.</param>
        <param name="storageAccountAttributes">Die Attribute des Speicherkontos.</param>
        <param name="tags">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</param>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountUpdateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveKeyName">
      <MemberSignature Language="C#" Value="public string ActiveKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActiveKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.ActiveKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActiveKeyName As String" />
      <MemberSignature Language="F#" Value="member this.ActiveKeyName : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.ActiveKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activeKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der aktuellen aktiven Schlüssel den Namen des Speicherkontos.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRegenerateKey">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoRegenerateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoRegenerateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.AutoRegenerateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRegenerateKey As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoRegenerateKey : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.AutoRegenerateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoRegenerateKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob Keyvault das Speicherkonto für den Benutzer verwalten soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerationPeriod">
      <MemberSignature Language="C#" Value="public string RegenerationPeriod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegenerationPeriod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.RegenerationPeriod" />
      <MemberSignature Language="VB.NET" Value="Public Property RegenerationPeriod As String" />
      <MemberSignature Language="F#" Value="member this.RegenerationPeriod : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.RegenerationPeriod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="regenerationPeriod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountAttributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.StorageAccountAttributes StorageAccountAttributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes StorageAccountAttributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.StorageAccountAttributes" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountAttributes As StorageAccountAttributes" />
      <MemberSignature Language="F#" Value="member this.StorageAccountAttributes : Microsoft.Azure.KeyVault.Models.StorageAccountAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.StorageAccountAttributes" />
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
        <ReturnType>Microsoft.Azure.KeyVault.Models.StorageAccountAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Attribute des Speicherkontos.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountUpdateParameters.Tags" />
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
            Ruft ab oder legt Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>