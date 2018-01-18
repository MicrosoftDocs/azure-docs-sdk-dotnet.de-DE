<Type Name="ManagedIntegrationRuntimeOperationResult" FullName="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult">
  <TypeSignature Language="C#" Value="public class ManagedIntegrationRuntimeOperationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagedIntegrationRuntimeOperationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagedIntegrationRuntimeOperationResult" />
  <TypeSignature Language="F#" Value="type ManagedIntegrationRuntimeOperationResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92528-101">Eigenschaften des verwalteten Integration Runtime vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="92528-101">Properties of managed integration runtime operation result.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntimeOperationResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92528-102">Initialisiert eine neue Instanz der ManagedIntegrationRuntimeOperationResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="92528-102">Initializes a new instance of the ManagedIntegrationRuntimeOperationResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntimeOperationResult (string type = null, Nullable&lt;DateTime&gt; startTime = null, string result = null, string errorCode = null, System.Collections.Generic.IList&lt;string&gt; parameters = null, string activityId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, string result, string errorCode, class System.Collections.Generic.IList`1&lt;string&gt; parameters, string activityId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.#ctor(System.String,System.Nullable{System.DateTime},System.String,System.String,System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional result As String = null, Optional errorCode As String = null, Optional parameters As IList(Of String) = null, Optional activityId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult : string * Nullable&lt;DateTime&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult" Usage="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult (type, startTime, result, errorCode, parameters, activityId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="result" Type="System.String" />
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="activityId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="92528-103">Der Vorgangstyp.</span><span class="sxs-lookup"><span data-stu-id="92528-103">The operation type.</span></span> <span data-ttu-id="92528-104">Konnte werden starten oder beenden.</span><span class="sxs-lookup"><span data-stu-id="92528-104">Could be start or stop.</span></span></param>
        <param name="startTime"><span data-ttu-id="92528-105">Die Startzeit des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="92528-105">The start time of the operation.</span></span></param>
        <param name="result"><span data-ttu-id="92528-106">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="92528-106">The operation result.</span></span></param>
        <param name="errorCode"><span data-ttu-id="92528-107">Der Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="92528-107">The error code.</span></span></param>
        <param name="parameters"><span data-ttu-id="92528-108">Fehler Laufzeitparameter verwaltete Integration.</span><span class="sxs-lookup"><span data-stu-id="92528-108">Managed integration runtime error parameters.</span></span></param>
        <param name="activityId"><span data-ttu-id="92528-109">Die Aktivitäts-Id für die vorgangsanforderung.</span><span class="sxs-lookup"><span data-stu-id="92528-109">The activity id for the operation request.</span></span></param>
        <summary>
            <span data-ttu-id="92528-110">Initialisiert eine neue Instanz der ManagedIntegrationRuntimeOperationResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="92528-110">Initializes a new instance of the ManagedIntegrationRuntimeOperationResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.ActivityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activityId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92528-111">Ruft die Aktivitäts-Id für die vorgangsanforderung ab.</span><span class="sxs-lookup"><span data-stu-id="92528-111">Gets the activity id for the operation request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public string ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As String" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92528-112">Ruft den Fehlercode ab.</span><span class="sxs-lookup"><span data-stu-id="92528-112">Gets the error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92528-113">Ruft verwaltet Integration Laufzeitparameter-Fehler.</span><span class="sxs-lookup"><span data-stu-id="92528-113">Gets managed integration runtime error parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public string Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As String" />
      <MemberSignature Language="F#" Value="member this.Result : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="result")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92528-114">Ruft das Ergebnis des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="92528-114">Gets the operation result.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92528-115">Ruft die Startzeit des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="92528-115">Gets the start time of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="92528-116">Ruft den Vorgangstyp ab.</span><span class="sxs-lookup"><span data-stu-id="92528-116">Gets the operation type.</span></span> <span data-ttu-id="92528-117">Konnte werden starten oder beenden.</span><span class="sxs-lookup"><span data-stu-id="92528-117">Could be start or stop.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>