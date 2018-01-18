<Type Name="OperationInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner">
  <TypeSignature Language="C#" Value="public class OperationInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationInner" />
  <TypeSignature Language="F#" Value="type OperationInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="61a10-101">Der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="61a10-101">Operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61a10-102">Initialisiert eine neue Instanz der OperationInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61a10-102">Initializes a new instance of the OperationInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationInner (string id = null, string name = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ErrorEntity&gt; errors = null, Nullable&lt;DateTime&gt; createdTime = null, Nullable&lt;DateTime&gt; modifiedTime = null, Nullable&lt;DateTime&gt; expirationTime = null, string geoMasterOperationId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.OperationStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ErrorEntity&gt; errors, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; modifiedTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationTime, string geoMasterOperationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.OperationStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.ErrorEntity},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional status As Nullable(Of OperationStatus) = null, Optional errors As IList(Of ErrorEntity) = null, Optional createdTime As Nullable(Of DateTime) = null, Optional modifiedTime As Nullable(Of DateTime) = null, Optional expirationTime As Nullable(Of DateTime) = null, Optional geoMasterOperationId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner : string * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ErrorEntity&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner (id, name, status, errors, createdTime, modifiedTime, expirationTime, geoMasterOperationId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationStatus&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ErrorEntity&gt;" />
        <Parameter Name="createdTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="modifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="geoMasterOperationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="61a10-103">Vorgangs-ID</span><span class="sxs-lookup"><span data-stu-id="61a10-103">Operation ID.</span></span></param>
        <param name="name"><span data-ttu-id="61a10-104">Vorgangsname</span><span class="sxs-lookup"><span data-stu-id="61a10-104">Operation name.</span></span></param>
        <param name="status"><span data-ttu-id="61a10-105">Der aktuelle Status des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="61a10-105">The current status of the operation.</span></span> <span data-ttu-id="61a10-106">Folgende Werte sind möglich: "InProgress", "Fehler", "Succeeded", "TimedOut", "Erstellt"</span><span class="sxs-lookup"><span data-stu-id="61a10-106">Possible values include: 'InProgress', 'Failed', 'Succeeded', 'TimedOut', 'Created'</span></span></param>
        <param name="errors"><span data-ttu-id="61a10-107">Alle Fehler ordnen Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="61a10-107">Any errors associate with the operation.</span></span></param>
        <param name="createdTime"><span data-ttu-id="61a10-108">Uhrzeit, wann der Vorgang begonnen wurde.</span><span class="sxs-lookup"><span data-stu-id="61a10-108">Time when operation has started.</span></span></param>
        <param name="modifiedTime"><span data-ttu-id="61a10-109">Zeitpunkt, wenn der Vorgang aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="61a10-109">Time when operation has been updated.</span></span></param>
        <param name="expirationTime"><span data-ttu-id="61a10-110">Zeitpunkt, wann der Vorgang ablaufen soll.</span><span class="sxs-lookup"><span data-stu-id="61a10-110">Time when operation will expire.</span></span></param>
        <param name="geoMasterOperationId"><span data-ttu-id="61a10-111">Gilt nur für den Stempel Vorgangs-Ids.</span><span class="sxs-lookup"><span data-stu-id="61a10-111">Applicable only for stamp operation ids.</span></span></param>
        <summary>
            <span data-ttu-id="61a10-112">Initialisiert eine neue Instanz der OperationInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61a10-112">Initializes a new instance of the OperationInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createdTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a10-113">Ruft ab oder legt die Zeit, wenn der Vorgang gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="61a10-113">Gets or sets time when operation has started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ErrorEntity&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ErrorEntity&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of ErrorEntity)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ErrorEntity&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ErrorEntity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a10-114">Ermittelt oder definiert Fehler verknüpfen mit dem Vorgang.</span><span class="sxs-lookup"><span data-stu-id="61a10-114">Gets or sets any errors associate with the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a10-115">Abrufen oder Festlegen der Zeit, wann der Vorgang ablaufen soll.</span><span class="sxs-lookup"><span data-stu-id="61a10-115">Gets or sets time when operation will expire.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoMasterOperationId">
      <MemberSignature Language="C#" Value="public string GeoMasterOperationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GeoMasterOperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.GeoMasterOperationId" />
      <MemberSignature Language="VB.NET" Value="Public Property GeoMasterOperationId As String" />
      <MemberSignature Language="F#" Value="member this.GeoMasterOperationId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.GeoMasterOperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="geoMasterOperationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a10-116">Ruft ab, oder legt ihn fest gilt nur für den Stempel Vorgangs-Ids.</span><span class="sxs-lookup"><span data-stu-id="61a10-116">Gets or sets applicable only for stamp operation ids.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="61a10-117">Ruft ab oder legt die Vorgangs-ID.</span><span class="sxs-lookup"><span data-stu-id="61a10-117">Gets or sets operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ModifiedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.ModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ModifiedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.ModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="modifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a10-118">Abrufen oder Festlegen der Zeit, wenn der Vorgang aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="61a10-118">Gets or sets time when operation has been updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a10-119">Ruft ab, oder legt ihn fest Vorgangsnamen.</span><span class="sxs-lookup"><span data-stu-id="61a10-119">Gets or sets operation name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.OperationStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of OperationStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationStatus&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a10-120">Ruft ab oder legt den aktuellen Status des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="61a10-120">Gets or sets the current status of the operation.</span></span> <span data-ttu-id="61a10-121">Folgende Werte sind möglich: "InProgress", "Fehler", "Succeeded", "TimedOut", "Erstellt"</span><span class="sxs-lookup"><span data-stu-id="61a10-121">Possible values include: 'InProgress', 'Failed', 'Succeeded', 'TimedOut', 'Created'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>