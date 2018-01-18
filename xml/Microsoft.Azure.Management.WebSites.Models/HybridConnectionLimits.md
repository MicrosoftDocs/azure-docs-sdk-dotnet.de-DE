<Type Name="HybridConnectionLimits" FullName="Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits">
  <TypeSignature Language="C#" Value="public class HybridConnectionLimits : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionLimits extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionLimits&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type HybridConnectionLimits = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e2318-101">Hybridverbindung schränkt Vertrag.</span><span class="sxs-lookup"><span data-stu-id="e2318-101">Hybrid Connection limits contract.</span></span> <span data-ttu-id="e2318-102">Hiermit wird der Plan Grenzwerte von Hybridverbindungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="e2318-102">This is used to return the plan limits of Hybrid Connections.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionLimits ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2318-103">Initialisiert eine neue Instanz der HybridConnectionLimits-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e2318-103">Initializes a new instance of the HybridConnectionLimits class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionLimits (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; current = null, Nullable&lt;int&gt; maximum = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; current, valuetype System.Nullable`1&lt;int32&gt; maximum) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional current As Nullable(Of Integer) = null, Optional maximum As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits : string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits" Usage="new Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits (id, name, kind, type, current, maximum)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="current" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maximum" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e2318-104">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="e2318-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="e2318-105">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="e2318-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="e2318-106">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="e2318-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="e2318-107">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="e2318-107">Resource type.</span></span></param>
        <param name="current"><span data-ttu-id="e2318-108">Die aktuelle Anzahl von Hybridverbindungen.</span><span class="sxs-lookup"><span data-stu-id="e2318-108">The current number of Hybrid Connections.</span></span></param>
        <param name="maximum"><span data-ttu-id="e2318-109">Die maximale Anzahl von Hybridverbindungen zulässig.</span><span class="sxs-lookup"><span data-stu-id="e2318-109">The maximum number of Hybrid Connections allowed.</span></span></param>
        <summary>
            <span data-ttu-id="e2318-110">Initialisiert eine neue Instanz der HybridConnectionLimits-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e2318-110">Initializes a new instance of the HybridConnectionLimits class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Current">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Current { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Current" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits.Current" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Current As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Current : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits.Current" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.current")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2318-111">Ruft die aktuelle Anzahl der Hybridverbindungen ab.</span><span class="sxs-lookup"><span data-stu-id="e2318-111">Gets the current number of Hybrid Connections.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Maximum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Maximum As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Maximum : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maximum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2318-112">Ruft die maximale Anzahl von Hybridverbindungen zulässig.</span><span class="sxs-lookup"><span data-stu-id="e2318-112">Gets the maximum number of Hybrid Connections allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>