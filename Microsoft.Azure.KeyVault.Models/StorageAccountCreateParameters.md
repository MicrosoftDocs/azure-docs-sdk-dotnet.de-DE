<Type Name="StorageAccountCreateParameters" FullName="Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters">
  <TypeSignature Language="C#" Value="public class StorageAccountCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountCreateParameters" />
  <TypeSignature Language="F#" Value="type StorageAccountCreateParameters = class" />
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
            Das Speicherkonto Parameter erstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParameters (string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.#ctor(System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters : string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters" Usage="new Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters (resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Boolean" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="resourceId">Ressourcen-Id des Speicher-Konto.</param>
        <param name="activeKeyName">Aktuelle aktive Key Name des Speicherkontos.</param>
        <param name="autoRegenerateKey">Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.</param>
        <param name="regenerationPeriod">Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.</param>
        <param name="storageAccountAttributes">Die Attribute des Speicherkontos.</param>
        <param name="tags">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</param>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveKeyName">
      <MemberSignature Language="C#" Value="public string ActiveKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActiveKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.ActiveKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActiveKeyName As String" />
      <MemberSignature Language="F#" Value="member this.ActiveKeyName : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.ActiveKeyName" />
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
            Ruft ab, oder legt ihn fest aktuellen aktiven Schlüssel Name des Speicherkontos.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRegenerateKey">
      <MemberSignature Language="C#" Value="public bool AutoRegenerateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoRegenerateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.AutoRegenerateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRegenerateKey As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoRegenerateKey : bool with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.AutoRegenerateKey" />
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
        <ReturnType>System.Boolean</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.RegenerationPeriod" />
      <MemberSignature Language="VB.NET" Value="Public Property RegenerationPeriod As String" />
      <MemberSignature Language="F#" Value="member this.RegenerationPeriod : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.RegenerationPeriod" />
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
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt die Storage-Konto-Ressourcen-Id fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountAttributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.StorageAccountAttributes StorageAccountAttributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes StorageAccountAttributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.StorageAccountAttributes" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountAttributes As StorageAccountAttributes" />
      <MemberSignature Language="F#" Value="member this.StorageAccountAttributes : Microsoft.Azure.KeyVault.Models.StorageAccountAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.StorageAccountAttributes" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.Tags" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.StorageAccountCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>