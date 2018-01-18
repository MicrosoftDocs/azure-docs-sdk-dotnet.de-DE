<Type Name="ServerUsage" FullName="Microsoft.Azure.Management.Sql.Models.ServerUsage">
  <TypeSignature Language="C#" Value="public class ServerUsage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServerUsage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServerUsage" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerUsage" />
  <TypeSignature Language="F#" Value="type ServerUsage = class" />
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
            <span data-ttu-id="b1aec-101">Stellt servermetriken dar.</span><span class="sxs-lookup"><span data-stu-id="b1aec-101">Represents server metrics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerUsage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b1aec-102">Initialisiert eine neue Instanz der ServerUsage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b1aec-102">Initializes a new instance of the ServerUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerUsage (string name = null, string resourceName = null, string displayName = null, Nullable&lt;double&gt; currentValue = null, Nullable&lt;double&gt; limit = null, string unit = null, Nullable&lt;DateTime&gt; nextResetTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string resourceName, string displayName, valuetype System.Nullable`1&lt;float64&gt; currentValue, valuetype System.Nullable`1&lt;float64&gt; limit, string unit, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextResetTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerUsage.#ctor(System.String,System.String,System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional resourceName As String = null, Optional displayName As String = null, Optional currentValue As Nullable(Of Double) = null, Optional limit As Nullable(Of Double) = null, Optional unit As String = null, Optional nextResetTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServerUsage : string * string * string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ServerUsage" Usage="new Microsoft.Azure.Management.Sql.Models.ServerUsage (name, resourceName, displayName, currentValue, limit, unit, nextResetTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="nextResetTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="b1aec-103">Der Name der Metrik Auslastung Server.</span><span class="sxs-lookup"><span data-stu-id="b1aec-103">Name of the server usage metric.</span></span></param>
        <param name="resourceName"><span data-ttu-id="b1aec-104">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="b1aec-104">The name of the resource.</span></span></param>
        <param name="displayName"><span data-ttu-id="b1aec-105">Der Metrik Anzeigename.</span><span class="sxs-lookup"><span data-stu-id="b1aec-105">The metric display name.</span></span></param>
        <param name="currentValue"><span data-ttu-id="b1aec-106">Der aktuelle Wert der Metrik.</span><span class="sxs-lookup"><span data-stu-id="b1aec-106">The current value of the metric.</span></span></param>
        <param name="limit"><span data-ttu-id="b1aec-107">Der aktuelle Grenzwert für die Metrik.</span><span class="sxs-lookup"><span data-stu-id="b1aec-107">The current limit of the metric.</span></span></param>
        <param name="unit"><span data-ttu-id="b1aec-108">Die Einheiten der Metrik.</span><span class="sxs-lookup"><span data-stu-id="b1aec-108">The units of the metric.</span></span></param>
        <param name="nextResetTime"><span data-ttu-id="b1aec-109">Das nächste zurückgesetzt Mal für die Metrik (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="b1aec-109">The next reset time for the metric (ISO8601 format).</span></span></param>
        <summary>
            <span data-ttu-id="b1aec-110">Initialisiert eine neue Instanz der ServerUsage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b1aec-110">Initializes a new instance of the ServerUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServerUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1aec-111">Ruft den aktuellen Wert der Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="b1aec-111">Gets the current value of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUsage.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerUsage.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1aec-112">Ruft die Metrik Anzeigenamen ab.</span><span class="sxs-lookup"><span data-stu-id="b1aec-112">Gets the metric display name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServerUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1aec-113">Ruft die aktuelle Grenze für die Metrik ab.</span><span class="sxs-lookup"><span data-stu-id="b1aec-113">Gets the current limit of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUsage.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerUsage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="b1aec-114">Ruft die Namen der Metrik Auslastung Server ab.</span><span class="sxs-lookup"><span data-stu-id="b1aec-114">Gets name of the server usage metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextResetTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextResetTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextResetTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUsage.NextResetTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextResetTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextResetTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServerUsage.NextResetTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextResetTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1aec-115">Ruft der nächsten zurücksetzen Zeit für die Metrik (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="b1aec-115">Gets the next reset time for the metric (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceName">
      <MemberSignature Language="C#" Value="public string ResourceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUsage.ResourceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceName : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerUsage.ResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1aec-116">Ruft den Namen der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="b1aec-116">Gets the name of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1aec-117">Ruft die Einheiten der Metrik an.</span><span class="sxs-lookup"><span data-stu-id="b1aec-117">Gets the units of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>