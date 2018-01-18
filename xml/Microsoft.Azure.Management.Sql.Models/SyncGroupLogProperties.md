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
            <span data-ttu-id="d5e70-101">Die Eigenschaften eines Azure SQL-Datenbank Sync-Gruppe an.</span><span class="sxs-lookup"><span data-stu-id="d5e70-101">Properties of an Azure SQL Database sync group log.</span></span>
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
            <span data-ttu-id="d5e70-102">Initialisiert eine neue Instanz der SyncGroupLogProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d5e70-102">Initializes a new instance of the SyncGroupLogProperties class.</span></span>
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
        <param name="timestamp"><span data-ttu-id="d5e70-103">Zeitstempel, der das Protokoll der Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="d5e70-103">Timestamp of the sync group log.</span></span></param>
        <param name="type"><span data-ttu-id="d5e70-104">Der Typ des Protokolls Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="d5e70-104">Type of the sync group log.</span></span> <span data-ttu-id="d5e70-105">Folgende Werte sind möglich: "Alle", "Fehler", "Warnung", "Success"</span><span class="sxs-lookup"><span data-stu-id="d5e70-105">Possible values include: 'All', 'Error', 'Warning', 'Success'</span></span></param>
        <param name="source"><span data-ttu-id="d5e70-106">Die Quelle des Protokolls Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="d5e70-106">Source of the sync group log.</span></span></param>
        <param name="details"><span data-ttu-id="d5e70-107">Details des Protokolls Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="d5e70-107">Details of the sync group log.</span></span></param>
        <param name="tracingId"><span data-ttu-id="d5e70-108">Tracingid darf des Protokolls Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="d5e70-108">TracingId of the sync group log.</span></span></param>
        <param name="operationStatus"><span data-ttu-id="d5e70-109">OperationStatus des Protokolls Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="d5e70-109">OperationStatus of the sync group log.</span></span></param>
        <summary>
            <span data-ttu-id="d5e70-110">Initialisiert eine neue Instanz der SyncGroupLogProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d5e70-110">Initializes a new instance of the SyncGroupLogProperties class.</span></span>
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
            <span data-ttu-id="d5e70-111">Ruft die Details des Sync-Gruppe-Protokolls ab.</span><span class="sxs-lookup"><span data-stu-id="d5e70-111">Gets details of the sync group log.</span></span>
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
            <span data-ttu-id="d5e70-112">Ruft die OperationStatus des Sync-Gruppe-Protokolls ab.</span><span class="sxs-lookup"><span data-stu-id="d5e70-112">Gets operationStatus of the sync group log.</span></span>
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
            <span data-ttu-id="d5e70-113">Ruft die Quelle des Sync-Gruppe-Protokolls ab.</span><span class="sxs-lookup"><span data-stu-id="d5e70-113">Gets source of the sync group log.</span></span>
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
            <span data-ttu-id="d5e70-114">Ruft die Zeitstempel des Sync-Gruppe-Protokolls ab.</span><span class="sxs-lookup"><span data-stu-id="d5e70-114">Gets timestamp of the sync group log.</span></span>
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
            <span data-ttu-id="d5e70-115">Ruft die tracingid darf des Sync-Gruppe-Protokolls ab.</span><span class="sxs-lookup"><span data-stu-id="d5e70-115">Gets tracingId of the sync group log.</span></span>
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
            <span data-ttu-id="d5e70-116">Ruft den Typ des Protokolls Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="d5e70-116">Gets type of the sync group log.</span></span> <span data-ttu-id="d5e70-117">Folgende Werte sind möglich: "Alle", "Fehler", "Warnung", "Success"</span><span class="sxs-lookup"><span data-stu-id="d5e70-117">Possible values include: 'All', 'Error', 'Warning', 'Success'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>