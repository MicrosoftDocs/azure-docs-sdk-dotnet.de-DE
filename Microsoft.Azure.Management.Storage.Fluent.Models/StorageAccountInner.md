<Type Name="StorageAccountInner" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner">
  <TypeSignature Language="C#" Value="public class StorageAccountInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type StorageAccountInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Das Speicherkonto.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; kind = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; provisioningState = null, Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints primaryEndpoints = null, string primaryLocation = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; statusOfPrimary = null, Nullable&lt;DateTime&gt; lastGeoFailoverTime = null, string secondaryLocation = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; statusOfSecondary = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints secondaryEndpoints = null, Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; provisioningState, class Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints primaryEndpoints, string primaryLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; statusOfPrimary, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastGeoFailoverTime, string secondaryLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; statusOfSecondary, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints secondaryEndpoints, class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Fluent.Models.Sku,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.Kind},System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState},Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints,System.String,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus},System.Nullable{System.DateTime},System.String,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus},System.Nullable{System.DateTime},Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain,Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints,Microsoft.Azure.Management.Storage.Fluent.Models.Encryption,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.Sku * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints * string * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain * Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints * Microsoft.Azure.Management.Storage.Fluent.Models.Encryption * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner (location, id, name, type, tags, sku, kind, provisioningState, primaryEndpoints, primaryLocation, statusOfPrimary, lastGeoFailoverTime, secondaryLocation, statusOfSecondary, creationTime, customDomain, secondaryEndpoints, encryption, accessTier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Sku" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt;" />
        <Parameter Name="primaryEndpoints" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints" />
        <Parameter Name="primaryLocation" Type="System.String" />
        <Parameter Name="statusOfPrimary" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;" />
        <Parameter Name="lastGeoFailoverTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="secondaryLocation" Type="System.String" />
        <Parameter Name="statusOfSecondary" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
        <Parameter Name="secondaryEndpoints" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="sku">Ruft die SKU.</param>
        <param name="kind">Ruft den Typ ab. Folgende Werte sind möglich: "Speicher", "BlobStorage"</param>
        <param name="provisioningState">Ruft den Status des Speicherkontos zu dem Zeitpunkt, der Vorgang aufgerufen wurde. Folgende Werte sind möglich: "Erstellen", "ResolvingDNS", "erfolgreich abgeschlossen"</param>
        <param name="primaryEndpoints">Ruft die URLs, die für den Abruf von einer öffentlichen BLOB-, Warteschlangen- oder Tabellenobjekts verwendet werden. Beachten Sie, dass die Konten "standard_zrs" und "premium_lrs" nur der blobendpunkt zurückgegeben.</param>
        <param name="primaryLocation">Ruft den Speicherort der primären Rechenzentrum für das Speicherkonto an.</param>
        <param name="statusOfPrimary">Ruft den Status, der angibt, ob der primäre Speicherort des Speicherkontos verfügbar oder nicht verfügbar ist. Folgende Werte sind möglich: "Verfügbar", "Nicht verfügbar"</param>
        <param name="lastGeoFailoverTime">Ruft den Zeitstempel der letzten Instanz eines Failovers zum sekundären Speicherort ab. Nur die neueste Zeitstempel wird beibehalten. Dieses Element wird nicht zurückgegeben, wenn es nie eine Failoverinstanz noch war. Nur verfügbar, wenn die AccountType Standard_GRS oder Standard_RAGRS ist.</param>
        <param name="secondaryLocation">Ruft den Speicherort der sekundären Datenbank geografisch repliziert, für das Speicherkonto an. Nur verfügbar, wenn die AccountType Standard_GRS oder Standard_RAGRS ist.</param>
        <param name="statusOfSecondary">Ruft den Status, der angibt, ob der sekundäre Standort des Speicherkontos verfügbar oder nicht verfügbar ist. Nur verfügbar, wenn der SKU-Name Standard_GRS oder Standard_RAGRS ist. Folgende Werte sind möglich: "Verfügbar", "Nicht verfügbar"</param>
        <param name="creationTime">Ruft das Erstellungsdatum und die Uhrzeit des Speicherkontos (UTC) an.</param>
        <param name="customDomain">Ruft der benutzerdefinierten Domäne für dieses Speicherkonto zugewiesene Benutzer ab.</param>
        <param name="secondaryEndpoints">Ruft die URLs, die für den Abruf von einer öffentlichen BLOB-, Warteschlangen- oder Tabellenobjekts aus dem sekundären Standort des Speicherkontos verwendet werden. Nur verfügbar, wenn der SKU-Name Standard_RAGRS ist.</param>
        <param name="encryption">Ruft die Einstellungen für die Verschlüsselung für das Konto an. Falls nicht angegeben, ist das Konto unverschlüsselt.</param>
        <param name="accessTier">Erforderlich für Speicherkonten, Kind = BlobStorage. Der Access-Ebene für die Abrechnung verwendet. Folgende Werte sind möglich: "Hot", "Super"</param>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft erforderlich, für Speicherkonten, Kind = BlobStorage. Der Access-Ebene für die Abrechnung verwendet. Folgende Werte sind möglich: "Hot", "Super"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Erstellungsdatum und die Uhrzeit des Speicherkontos (UTC) an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der benutzerdefinierten Domäne für dieses Speicherkonto zugewiesene Benutzer ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Einstellungen für die Verschlüsselung für das Konto an. Falls nicht angegeben, ist das Konto unverschlüsselt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As Nullable(Of Kind)" />
      <MemberSignature Language="F#" Value="member this.Kind : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ ab. Folgende Werte sind möglich: "Speicher", "BlobStorage"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastGeoFailoverTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastGeoFailoverTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastGeoFailoverTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.LastGeoFailoverTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastGeoFailoverTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastGeoFailoverTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.LastGeoFailoverTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastGeoFailoverTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitstempel der letzten Instanz eines Failovers zum sekundären Speicherort ab. Nur die neueste Zeitstempel wird beibehalten.
            Dieses Element wird nicht zurückgegeben, wenn es nie eine Failoverinstanz noch war. Nur verfügbar, wenn die AccountType Standard_GRS oder Standard_RAGRS ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryEndpoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints PrimaryEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints PrimaryEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.PrimaryEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryEndpoints As Endpoints" />
      <MemberSignature Language="F#" Value="member this.PrimaryEndpoints : Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.PrimaryEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die URLs, die für den Abruf von einer öffentlichen BLOB-, Warteschlangen- oder Tabellenobjekts verwendet werden. Beachten Sie, dass die Konten "standard_zrs" und "premium_lrs" nur der blobendpunkt zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryLocation">
      <MemberSignature Language="C#" Value="public string PrimaryLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.PrimaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryLocation : string" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.PrimaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Speicherort der primären Rechenzentrum für das Speicherkonto an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des Speicherkontos zu dem Zeitpunkt, der Vorgang aufgerufen wurde. Folgende Werte sind möglich: "Erstellen", "ResolvingDNS", "erfolgreich abgeschlossen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryEndpoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints SecondaryEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints SecondaryEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.SecondaryEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryEndpoints As Endpoints" />
      <MemberSignature Language="F#" Value="member this.SecondaryEndpoints : Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.SecondaryEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die URLs, die für den Abruf von einer öffentlichen BLOB-, Warteschlangen- oder Tabellenobjekts aus dem sekundären Standort des Speicherkontos verwendet werden. Nur verfügbar, wenn der SKU-Name Standard_RAGRS ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryLocation">
      <MemberSignature Language="C#" Value="public string SecondaryLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.SecondaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryLocation : string" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.SecondaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Speicherort der sekundären Datenbank geografisch repliziert, für das Speicherkonto an. Nur verfügbar, wenn die AccountType Standard_GRS oder Standard_RAGRS ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die SKU.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusOfPrimary">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; StatusOfPrimary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; StatusOfPrimary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.StatusOfPrimary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusOfPrimary As Nullable(Of AccountStatus)" />
      <MemberSignature Language="F#" Value="member this.StatusOfPrimary : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.StatusOfPrimary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusOfPrimary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status, der angibt, ob der primäre Speicherort des Speicherkontos verfügbar oder nicht verfügbar ist. Folgende Werte sind möglich: "Verfügbar", "Nicht verfügbar"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusOfSecondary">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; StatusOfSecondary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; StatusOfSecondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.StatusOfSecondary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusOfSecondary As Nullable(Of AccountStatus)" />
      <MemberSignature Language="F#" Value="member this.StatusOfSecondary : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.StatusOfSecondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusOfSecondary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status, der angibt, ob der sekundäre Standort des Speicherkontos verfügbar oder nicht verfügbar ist. Nur verfügbar, wenn der SKU-Name Standard_GRS oder Standard_RAGRS ist. Folgende Werte sind möglich: "Verfügbar", "Nicht verfügbar"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="storageAccountInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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