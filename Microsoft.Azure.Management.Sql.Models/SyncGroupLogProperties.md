<Type Name="SyncGroupLogProperties" FullName="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties">
  <TypeSignature Language="C#" Value="public class SyncGroupLogProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncGroupLogProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncGroupLogProperties" />
  <TypeSignature Language="F#" Value="type SyncGroupLogProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Eigenschaften eines Azure SQL-Datenbank Sync-Gruppe an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupLogProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SyncGroupLogProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupLogProperties (Nullable&lt;DateTime&gt; timestamp = null, string type = null, string source = null, string details = null, Nullable&lt;Guid&gt; tracingId = null, string operationStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestamp, string type, string source, string details, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tracingId, string operationStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.#ctor(System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Guid},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timestamp As Nullable(Of DateTime) = null, Optional type As String = null, Optional source As String = null, Optional details As String = null, Optional tracingId As Nullable(Of Guid) = null, Optional operationStatus As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties : Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;Guid&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties" Usage="new Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties (timestamp, type, source, details, tracingId, operationStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="details" Type="System.String" />
        <Parameter Name="tracingId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="operationStatus" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timestamp">Zeitstempel, der das Protokoll der Sync-Gruppe.</param>
        <param name="type">Der Typ des Protokolls Sync-Gruppe. Folgende Werte sind möglich: "Alle", "Fehler", "Warnung", "Success"</param>
        <param name="source">Die Quelle des Protokolls Sync-Gruppe.</param>
        <param name="details">Details des Protokolls Sync-Gruppe.</param>
        <param name="tracingId">Tracingid darf des Protokolls Sync-Gruppe.</param>
        <param name="operationStatus">OperationStatus des Protokolls Sync-Gruppe.</param>
        <summary>
            Initialisiert eine neue Instanz der SyncGroupLogProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Details des Sync-Gruppe-Protokolls ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationStatus">
      <MemberSignature Language="C#" Value="public string OperationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.OperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationStatus As String" />
      <MemberSignature Language="F#" Value="member this.OperationStatus : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.OperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die OperationStatus des Sync-Gruppe-Protokolls ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Quelle des Sync-Gruppe-Protokolls ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeitstempel des Sync-Gruppe-Protokolls ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TracingId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TracingId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TracingId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.TracingId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TracingId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TracingId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.TracingId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tracingId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die tracingid darf des Sync-Gruppe-Protokolls ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ des Protokolls Sync-Gruppe. Folgende Werte sind möglich: "Alle", "Fehler", "Warnung", "Success"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>