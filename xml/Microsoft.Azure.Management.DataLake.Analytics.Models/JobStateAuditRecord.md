<Type Name="JobStateAuditRecord" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord">
  <TypeSignature Language="C#" Value="public class JobStateAuditRecord" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStateAuditRecord extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStateAuditRecord" />
  <TypeSignature Language="F#" Value="type JobStateAuditRecord = class" />
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
            <span data-ttu-id="1aeff-101">Data Lake Analytics-Auftrag Zustand Audit-Datensätze für das Nachverfolgen des Lebenszyklus eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="1aeff-101">The Data Lake Analytics job state audit records for tracking the lifecycle of a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStateAuditRecord ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1aeff-102">Initialisiert eine neue Instanz der JobStateAuditRecord-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1aeff-102">Initializes a new instance of the JobStateAuditRecord class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStateAuditRecord (string newState = null, Nullable&lt;DateTimeOffset&gt; timeStamp = null, string requestedByUser = null, string details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string newState, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; timeStamp, string requestedByUser, string details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.#ctor(System.String,System.Nullable{System.DateTimeOffset},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional newState As String = null, Optional timeStamp As Nullable(Of DateTimeOffset) = null, Optional requestedByUser As String = null, Optional details As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord : string * Nullable&lt;DateTimeOffset&gt; * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord (newState, timeStamp, requestedByUser, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="newState" Type="System.String" />
        <Parameter Name="timeStamp" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="requestedByUser" Type="System.String" />
        <Parameter Name="details" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="newState"><span data-ttu-id="1aeff-103">der neue Status des Auftrags wird.</span><span class="sxs-lookup"><span data-stu-id="1aeff-103">the new state the job is in.</span></span></param>
        <param name="timeStamp"><span data-ttu-id="1aeff-104">der Zeitstempel, der dem Statuswechsel hat stattgefunden.</span><span class="sxs-lookup"><span data-stu-id="1aeff-104">the time stamp that the state change took place.</span></span></param>
        <param name="requestedByUser"><span data-ttu-id="1aeff-105">der Benutzer, der die Änderung anfordert.</span><span class="sxs-lookup"><span data-stu-id="1aeff-105">the user who requests the change.</span></span></param>
        <param name="details"><span data-ttu-id="1aeff-106">die Details des Überwachungsprotokolls.</span><span class="sxs-lookup"><span data-stu-id="1aeff-106">the details of the audit log.</span></span></param>
        <summary>
            <span data-ttu-id="1aeff-107">Initialisiert eine neue Instanz der JobStateAuditRecord-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1aeff-107">Initializes a new instance of the JobStateAuditRecord class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="1aeff-108">Ruft die Details des Überwachungsprotokolls ab.</span><span class="sxs-lookup"><span data-stu-id="1aeff-108">Gets the details of the audit log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewState">
      <MemberSignature Language="C#" Value="public string NewState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NewState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.NewState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NewState As String" />
      <MemberSignature Language="F#" Value="member this.NewState : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.NewState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="newState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1aeff-109">Ruft den neuen Status, dem der Auftrag hat.</span><span class="sxs-lookup"><span data-stu-id="1aeff-109">Gets the new state the job is in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedByUser">
      <MemberSignature Language="C#" Value="public string RequestedByUser { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedByUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.RequestedByUser" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedByUser As String" />
      <MemberSignature Language="F#" Value="member this.RequestedByUser : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.RequestedByUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requestedByUser")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1aeff-110">Erhält der Benutzer, der die Änderung anfordert.</span><span class="sxs-lookup"><span data-stu-id="1aeff-110">Gets the user who requests the change.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; TimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; TimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.TimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeStamp As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.TimeStamp : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord.TimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1aeff-111">Ruft der Zeitstempel, den Status ändert, ausgeführten platzieren.</span><span class="sxs-lookup"><span data-stu-id="1aeff-111">Gets the time stamp that the state change took place.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>