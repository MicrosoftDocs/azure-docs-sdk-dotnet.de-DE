<Type Name="DataSource" FullName="Microsoft.Azure.Management.OperationalInsights.Models.DataSource">
  <TypeSignature Language="C#" Value="public class DataSource : Microsoft.Azure.Management.OperationalInsights.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSource extends Microsoft.Azure.Management.OperationalInsights.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.DataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSource&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DataSource = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.OperationalInsights.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="50f22-101">Datenquellen in OMS-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="50f22-101">Datasources under OMS Workspace.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.DataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="50f22-102">Initialisiert eine neue Instanz der DataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50f22-102">Initializes a new instance of the DataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource (object properties, string kind, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object properties, string kind, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.DataSource.#ctor(System.Object,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (properties As Object, kind As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.DataSource : obj * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.DataSource" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.DataSource (properties, kind, id, name, type, tags, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="properties" Type="System.Object" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="50f22-103">Die Datenquelleneigenschaften im unformatierten Json-Format, jede Art von Datenquelle haben eigene Schemas.</span><span class="sxs-lookup"><span data-stu-id="50f22-103">The data source properties in raw json format, each kind of data source have it's own schema.</span></span></param>
        <param name="kind"><span data-ttu-id="50f22-104">Folgende Werte sind möglich: "AzureActivityLog", "ChangeTrackingPath", "ChangeTrackingDefaultPath", "ChangeTrackingDefaultRegistry", "ChangeTrackingCustomRegistry", "CustomLog", "CustomLogCollection", "GenericDataSource", "IISLogs", "LinuxPerformanceObject", "LinuxPerformanceCollection", "LinuxSyslog", "LinuxSyslogCollection", "WindowsEvent", "WindowsPerformanceCounter"</span><span class="sxs-lookup"><span data-stu-id="50f22-104">Possible values include: 'AzureActivityLog', 'ChangeTrackingPath', 'ChangeTrackingDefaultPath', 'ChangeTrackingDefaultRegistry', 'ChangeTrackingCustomRegistry', 'CustomLog', 'CustomLogCollection', 'GenericDataSource', 'IISLogs', 'LinuxPerformanceObject', 'LinuxPerformanceCollection', 'LinuxSyslog', 'LinuxSyslogCollection', 'WindowsEvent', 'WindowsPerformanceCounter'</span></span></param>
        <param name="id"><span data-ttu-id="50f22-105">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="50f22-105">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="50f22-106">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="50f22-106">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="50f22-107">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="50f22-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="50f22-108">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="50f22-108">Resource tags</span></span></param>
        <param name="eTag"><span data-ttu-id="50f22-109">Das ETag der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="50f22-109">The ETag of the data source.</span></span></param>
        <summary>
            <span data-ttu-id="50f22-110">Initialisiert eine neue Instanz der DataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50f22-110">Initializes a new instance of the DataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.DataSource.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.DataSource.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50f22-111">Ruft ab oder legt das ETag der Datenquelle fest.</span><span class="sxs-lookup"><span data-stu-id="50f22-111">Gets or sets the ETag of the data source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.DataSource.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.DataSource.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50f22-112">Ruft ab oder legt folgende Werte möglich sind: "AzureActivityLog" "ChangeTrackingPath" "ChangeTrackingDefaultPath" "ChangeTrackingDefaultRegistry" "ChangeTrackingCustomRegistry" "CustomLog" "CustomLogCollection", "GenericDataSource", " IISLogs', 'LinuxPerformanceObject', "LinuxPerformanceCollection", "LinuxSyslog", "LinuxSyslogCollection", "WindowsEvent", "WindowsPerformanceCounter"</span><span class="sxs-lookup"><span data-stu-id="50f22-112">Gets or sets possible values include: 'AzureActivityLog', 'ChangeTrackingPath', 'ChangeTrackingDefaultPath', 'ChangeTrackingDefaultRegistry', 'ChangeTrackingCustomRegistry', 'CustomLog', 'CustomLogCollection', 'GenericDataSource', 'IISLogs', 'LinuxPerformanceObject', 'LinuxPerformanceCollection', 'LinuxSyslog', 'LinuxSyslogCollection', 'WindowsEvent', 'WindowsPerformanceCounter'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public object Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.DataSource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As Object" />
      <MemberSignature Language="F#" Value="member this.Properties : obj with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.DataSource.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50f22-113">Abrufen oder Festlegen der Datenquelle haben Eigenschaften im unformatierten Json-Format, jede Art von Datenquelle seinem eigenen Schemas.</span><span class="sxs-lookup"><span data-stu-id="50f22-113">Gets or sets the data source properties in raw json format, each kind of data source have it's own schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.DataSource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataSource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="50f22-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="50f22-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="50f22-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="50f22-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>