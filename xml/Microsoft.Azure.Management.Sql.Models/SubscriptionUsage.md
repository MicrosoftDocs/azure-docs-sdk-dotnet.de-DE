<Type Name="SubscriptionUsage" FullName="Microsoft.Azure.Management.Sql.Models.SubscriptionUsage">
  <TypeSignature Language="C#" Value="public class SubscriptionUsage : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionUsage extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SubscriptionUsage" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionUsage&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type SubscriptionUsage = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="dcfaf-101">Verwendung Metrik eines Abonnements an einem Ort.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-101">Usage Metric of a Subscription in a Location.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dcfaf-102">Initialisiert eine neue Instanz der SubscriptionUsage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-102">Initializes a new instance of the SubscriptionUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionUsage (string id = null, string name = null, string type = null, string displayName = null, Nullable&lt;double&gt; currentValue = null, Nullable&lt;double&gt; limit = null, string unit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string displayName, valuetype System.Nullable`1&lt;float64&gt; currentValue, valuetype System.Nullable`1&lt;float64&gt; limit, string unit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional displayName As String = null, Optional currentValue As Nullable(Of Double) = null, Optional limit As Nullable(Of Double) = null, Optional unit As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SubscriptionUsage : string * string * string * string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.SubscriptionUsage" Usage="new Microsoft.Azure.Management.Sql.Models.SubscriptionUsage (id, name, type, displayName, currentValue, limit, unit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="unit" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="dcfaf-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="dcfaf-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="dcfaf-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="dcfaf-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-105">Resource type.</span></span></param>
        <param name="displayName"><span data-ttu-id="dcfaf-106">Benutzer lesbaren Namen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-106">User-readable name of the metric.</span></span></param>
        <param name="currentValue"><span data-ttu-id="dcfaf-107">Aktuelle Wert der Metrik.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-107">Current value of the metric.</span></span></param>
        <param name="limit"><span data-ttu-id="dcfaf-108">Der Begrenzungswert der Metrik.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-108">Boundary value of the metric.</span></span></param>
        <param name="unit"><span data-ttu-id="dcfaf-109">Maßeinheit der Metrik.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-109">Unit of the metric.</span></span></param>
        <summary>
            <span data-ttu-id="dcfaf-110">Initialisiert eine neue Instanz der SubscriptionUsage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-110">Initializes a new instance of the SubscriptionUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dcfaf-111">Ruft die aktuelle Wert der Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-111">Gets current value of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dcfaf-112">Ruft die Metrik Benutzer lesbaren Namen ab.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-112">Gets user-readable name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dcfaf-113">Ruft Begrenzungswert der Metrik an.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-113">Gets boundary value of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Sql.Models.SubscriptionUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dcfaf-114">Ruft die Maßeinheit der Metrik.</span><span class="sxs-lookup"><span data-stu-id="dcfaf-114">Gets unit of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>