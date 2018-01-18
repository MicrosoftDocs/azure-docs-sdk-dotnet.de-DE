<Type Name="BillingPeriod" FullName="Microsoft.Azure.Management.Billing.Models.BillingPeriod">
  <TypeSignature Language="C#" Value="public class BillingPeriod : Microsoft.Azure.Management.Billing.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BillingPeriod extends Microsoft.Azure.Management.Billing.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Billing.Models.BillingPeriod" />
  <TypeSignature Language="VB.NET" Value="Public Class BillingPeriod&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BillingPeriod = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Billing.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="50ed4-101">Abrechnung Zeitraum Ressource.</span><span class="sxs-lookup"><span data-stu-id="50ed4-101">A billing period resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BillingPeriod ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.Models.BillingPeriod.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="50ed4-102">Initialisiert eine neue Instanz der BillingPeriod-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50ed4-102">Initializes a new instance of the BillingPeriod class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BillingPeriod (string id = null, string name = null, string type = null, Nullable&lt;DateTime&gt; billingPeriodStartDate = null, Nullable&lt;DateTime&gt; billingPeriodEndDate = null, System.Collections.Generic.IList&lt;string&gt; invoiceIds = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; billingPeriodStartDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; billingPeriodEndDate, class System.Collections.Generic.IList`1&lt;string&gt; invoiceIds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.Models.BillingPeriod.#ctor(System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional billingPeriodStartDate As Nullable(Of DateTime) = null, Optional billingPeriodEndDate As Nullable(Of DateTime) = null, Optional invoiceIds As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Billing.Models.BillingPeriod : string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Billing.Models.BillingPeriod" Usage="new Microsoft.Azure.Management.Billing.Models.BillingPeriod (id, name, type, billingPeriodStartDate, billingPeriodEndDate, invoiceIds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="billingPeriodStartDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="billingPeriodEndDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="invoiceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="50ed4-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="50ed4-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="50ed4-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="50ed4-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="50ed4-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="50ed4-105">Resource type.</span></span></param>
        <param name="billingPeriodStartDate"><span data-ttu-id="50ed4-106">Der Anfang des Datumsbereichs durch den Abrechnungszeitraum abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="50ed4-106">The start of the date range covered by the billing period.</span></span></param>
        <param name="billingPeriodEndDate"><span data-ttu-id="50ed4-107">Das Ende des Datumsbereichs durch den Abrechnungszeitraum abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="50ed4-107">The end of the date range covered by the billing period.</span></span></param>
        <param name="invoiceIds"><span data-ttu-id="50ed4-108">Array der Rechnung-Ids zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="50ed4-108">Array of invoice ids that associated with.</span></span></param>
        <summary>
            <span data-ttu-id="50ed4-109">Initialisiert eine neue Instanz der BillingPeriod-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50ed4-109">Initializes a new instance of the BillingPeriod class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BillingPeriodEndDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; BillingPeriodEndDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; BillingPeriodEndDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Billing.Models.BillingPeriod.BillingPeriodEndDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BillingPeriodEndDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.BillingPeriodEndDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Billing.Models.BillingPeriod.BillingPeriodEndDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.billingPeriodEndDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50ed4-110">Ruft das Ende des Datumsbereichs durch den Abrechnungszeitraum abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="50ed4-110">Gets the end of the date range covered by the billing period.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BillingPeriodStartDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; BillingPeriodStartDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; BillingPeriodStartDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Billing.Models.BillingPeriod.BillingPeriodStartDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BillingPeriodStartDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.BillingPeriodStartDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Billing.Models.BillingPeriod.BillingPeriodStartDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.billingPeriodStartDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50ed4-111">Ruft den Anfang des Datumsbereichs durch den Abrechnungszeitraum abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="50ed4-111">Gets the start of the date range covered by the billing period.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvoiceIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; InvoiceIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; InvoiceIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Billing.Models.BillingPeriod.InvoiceIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InvoiceIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.InvoiceIds : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Billing.Models.BillingPeriod.InvoiceIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.invoiceIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50ed4-112">Ruft Array der Rechnung-Ids zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="50ed4-112">Gets array of invoice ids that associated with.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>