<Type Name="DataLakeAnalyticsAccountPropertiesBasic" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsAccountPropertiesBasic" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsAccountPropertiesBasic extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsAccountPropertiesBasic" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsAccountPropertiesBasic = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die grundlegende Konto spezifischen Eigenschaften, die mit einem zugrunde liegenden Data Lake Analytics-Konto verknüpft sind.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountPropertiesBasic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsAccountPropertiesBasic-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountPropertiesBasic (Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;DateTime&gt; lastModifiedTime = null, string endpoint = null, Nullable&lt;Guid&gt; accountId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTime, string endpoint, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; accountId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.#ctor(System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provisioningState As Nullable(Of DataLakeAnalyticsAccountStatus) = null, Optional state As Nullable(Of DataLakeAnalyticsAccountState) = null, Optional creationTime As Nullable(Of DateTime) = null, Optional lastModifiedTime As Nullable(Of DateTime) = null, Optional endpoint As String = null, Optional accountId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic (provisioningState, state, creationTime, lastModifiedTime, endpoint, accountId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="accountId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="provisioningState">Der Bereitstellungsstatus des Data Lake Analytics-Kontos. Folgende Werte sind möglich: "Fehlgeschlagen", "Erstellen", "Wird ausgeführt", "Erfolgreich abgeschlossen", "Patchen", "Angehalten", "Fortsetzen", "Löschen", "Deleted"</param>
        <param name="state">der Status des Data Lake Analytics-Kontos.
            Folgende Werte sind möglich: "Aktiv", "Angehalten"</param>
        <param name="creationTime">die Erstellungszeit des Kontos.</param>
        <param name="lastModifiedTime">Zeitpunkt der letzten Änderung des Kontos.</param>
        <param name="endpoint">der vollständige CName-Endpunkt für dieses Konto.</param>
        <param name="accountId">Der eindeutige Bezeichner, der diesen Data Lake Analytics-Konto zugeordnet ist.</param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsAccountPropertiesBasic-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AccountId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AccountId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den eindeutigen Bezeichner dieses Data Lake Analytics-Konto zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Erstellungszeit des Kontos ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den vollständigen CName-Endpunkt für dieses Konto an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastModifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Uhrzeit der letzten Änderung des Kontos ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of DataLakeAnalyticsAccountStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bereitstellungsstatus des Data Lake Analytics-Kontos an.
            Folgende Werte sind möglich: "Fehlgeschlagen", "Erstellen", "Wird ausgeführt", "Erfolgreich abgeschlossen", "Patchen", "Angehalten", "Fortsetzen", "Löschen", "Deleted"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of DataLakeAnalyticsAccountState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des Data Lake Analytics-Kontos ab. Folgende Werte sind möglich: "Aktiv", "Angehalten"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>