<Type Name="ApplicationGatewaySku" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku">
  <TypeSignature Language="C#" Value="public class ApplicationGatewaySku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewaySku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewaySku" />
  <TypeSignature Language="F#" Value="type ApplicationGatewaySku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f167c-101">SKU des ein vorhandenes Anwendungsgateway</span><span class="sxs-lookup"><span data-stu-id="f167c-101">SKU of an application gateway</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f167c-102">Initialisiert eine neue Instanz der ApplicationGatewaySku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f167c-102">Initializes a new instance of the ApplicationGatewaySku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySku (string name = null, string tier = null, Nullable&lt;int&gt; capacity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier, valuetype System.Nullable`1&lt;int32&gt; capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku.#ctor(System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional tier As String = null, Optional capacity As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku : string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku (name, tier, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
        <Parameter Name="capacity" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f167c-103">Name des einen Anwendungsgateway SKU.</span><span class="sxs-lookup"><span data-stu-id="f167c-103">Name of an application gateway SKU.</span></span> <span data-ttu-id="f167c-104">Folgende Werte sind möglich: "Standard_Small", "Standard_Medium", "Standard_Large", "WAF_Medium", "WAF_Large"</span><span class="sxs-lookup"><span data-stu-id="f167c-104">Possible values include: 'Standard_Small', 'Standard_Medium', 'Standard_Large', 'WAF_Medium', 'WAF_Large'</span></span></param>
        <param name="tier"><span data-ttu-id="f167c-105">Ein vorhandenes Anwendungsgateway-Ebene:</span><span class="sxs-lookup"><span data-stu-id="f167c-105">Tier of an application gateway.</span></span> <span data-ttu-id="f167c-106">Folgende Werte sind möglich: "Standard", "WAF"</span><span class="sxs-lookup"><span data-stu-id="f167c-106">Possible values include: 'Standard', 'WAF'</span></span></param>
        <param name="capacity"><span data-ttu-id="f167c-107">Kapazität (instanzenanzahl) einen Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="f167c-107">Capacity (instance count) of an application gateway.</span></span></param>
        <summary>
            <span data-ttu-id="f167c-108">Initialisiert eine neue Instanz der ApplicationGatewaySku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f167c-108">Initializes a new instance of the ApplicationGatewaySku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Capacity : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f167c-109">Ermittelt oder definiert einen Anwendungsgateway Kapazität (instanzenanzahl).</span><span class="sxs-lookup"><span data-stu-id="f167c-109">Gets or sets capacity (instance count) of an application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f167c-110">Ruft ab, oder legt ihn fest Name, der ein vorhandenes Anwendungsgateway SKU.</span><span class="sxs-lookup"><span data-stu-id="f167c-110">Gets or sets name of an application gateway SKU.</span></span> <span data-ttu-id="f167c-111">Folgende Werte sind möglich: "Standard_Small", "Standard_Medium", "Standard_Large", "WAF_Medium", "WAF_Large"</span><span class="sxs-lookup"><span data-stu-id="f167c-111">Possible values include: 'Standard_Small', 'Standard_Medium', 'Standard_Large', 'WAF_Medium', 'WAF_Large'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f167c-112">Ermittelt oder definiert einen Anwendungsgateway Ebene.</span><span class="sxs-lookup"><span data-stu-id="f167c-112">Gets or sets tier of an application gateway.</span></span> <span data-ttu-id="f167c-113">Folgende Werte sind möglich: "Standard", "WAF"</span><span class="sxs-lookup"><span data-stu-id="f167c-113">Possible values include: 'Standard', 'WAF'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>