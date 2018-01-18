<Type Name="GlobalCsmSkuDescription" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription">
  <TypeSignature Language="C#" Value="public class GlobalCsmSkuDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GlobalCsmSkuDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class GlobalCsmSkuDescription" />
  <TypeSignature Language="F#" Value="type GlobalCsmSkuDescription = class" />
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
            <span data-ttu-id="2cc29-101">Eine globale SKU-Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="2cc29-101">A Global SKU Description.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GlobalCsmSkuDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2cc29-102">Initialisiert eine neue Instanz der GlobalCsmSkuDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2cc29-102">Initializes a new instance of the GlobalCsmSkuDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GlobalCsmSkuDescription (string name = null, string tier = null, Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity capacity = null, System.Collections.Generic.IList&lt;string&gt; locations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; capabilities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier, class Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity capacity, class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; capabilities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.#ctor(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional tier As String = null, Optional capacity As SkuCapacity = null, Optional locations As IList(Of String) = null, Optional capabilities As IList(Of CapabilityInner) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription (name, tier, capacity, locations, capabilities)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="capabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="2cc29-103">Der Name der Ressource SKU.</span><span class="sxs-lookup"><span data-stu-id="2cc29-103">Name of the resource SKU.</span></span></param>
        <param name="tier"><span data-ttu-id="2cc29-104">Die Dienstebene der Ressource SKU.</span><span class="sxs-lookup"><span data-stu-id="2cc29-104">Service Tier of the resource SKU.</span></span></param>
        <param name="capacity"><span data-ttu-id="2cc29-105">Min, Max und Skalierung Standardwerte der SKU.</span><span class="sxs-lookup"><span data-stu-id="2cc29-105">Min, max, and default scale values of the SKU.</span></span></param>
        <param name="locations"><span data-ttu-id="2cc29-106">Die Speicherorte der SKU.</span><span class="sxs-lookup"><span data-stu-id="2cc29-106">Locations of the SKU.</span></span></param>
        <param name="capabilities"><span data-ttu-id="2cc29-107">Funktionen von der SKU, z. B. Traffic Manager aktiviert ist?</span><span class="sxs-lookup"><span data-stu-id="2cc29-107">Capabilities of the SKU, e.g., is traffic manager enabled?</span></span></param>
        <summary>
            <span data-ttu-id="2cc29-108">Initialisiert eine neue Instanz der GlobalCsmSkuDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2cc29-108">Initializes a new instance of the GlobalCsmSkuDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; Capabilities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public Property Capabilities As IList(Of CapabilityInner)" />
      <MemberSignature Language="F#" Value="member this.Capabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cc29-109">Ruft ab oder legt Funktionen der SKU, z. B., ist Traffic Manager aktiviert?</span><span class="sxs-lookup"><span data-stu-id="2cc29-109">Gets or sets capabilities of the SKU, e.g., is traffic manager enabled?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As SkuCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SkuCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cc29-110">Ruft ab, oder legt sie fest, min, Max und Skalierung Standardwerte der SKU.</span><span class="sxs-lookup"><span data-stu-id="2cc29-110">Gets or sets min, max, and default scale values of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Locations" />
      <MemberSignature Language="VB.NET" Value="Public Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cc29-111">Ruft ab oder legt die Speicherorte der SKU.</span><span class="sxs-lookup"><span data-stu-id="2cc29-111">Gets or sets locations of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Name" />
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
            <span data-ttu-id="2cc29-112">Ruft ab oder legt den Namen der Ressource SKU fest.</span><span class="sxs-lookup"><span data-stu-id="2cc29-112">Gets or sets name of the resource SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="2cc29-113">Ruft ab oder legt die Ebene der Ressource SKU-Dienst.</span><span class="sxs-lookup"><span data-stu-id="2cc29-113">Gets or sets service Tier of the resource SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>