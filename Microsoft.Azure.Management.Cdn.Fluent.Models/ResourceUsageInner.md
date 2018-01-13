<Type Name="ResourceUsageInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner">
  <TypeSignature Language="C#" Value="public class ResourceUsageInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceUsageInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceUsageInner" />
  <TypeSignature Language="F#" Value="type ResourceUsageInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="38433-101">Die Ausgabe von Check-Ressourcenverwendung API.</span><span class="sxs-lookup"><span data-stu-id="38433-101">Output of check resource usage API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceUsageInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="38433-102">Initialisiert eine neue Instanz der Klasse ResourceUsage.</span><span class="sxs-lookup"><span data-stu-id="38433-102">Initializes a new instance of the ResourceUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceUsageInner (string resourceType = null, string unit = null, Nullable&lt;int&gt; currentValue = null, Nullable&lt;int&gt; limit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceType, string unit, valuetype System.Nullable`1&lt;int32&gt; currentValue, valuetype System.Nullable`1&lt;int32&gt; limit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.#ctor(System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceType As String = null, Optional unit As String = null, Optional currentValue As Nullable(Of Integer) = null, Optional limit As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner : string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner (resourceType, unit, currentValue, limit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="resourceType"><span data-ttu-id="38433-103">Der Ressourcentyp der Verwendungen.</span><span class="sxs-lookup"><span data-stu-id="38433-103">Resource type of the usages.</span></span></param>
        <param name="unit"><span data-ttu-id="38433-104">Die Einheit der Verwendung.</span><span class="sxs-lookup"><span data-stu-id="38433-104">Unit of the usage.</span></span> <span data-ttu-id="38433-105">z. B. die Anzahl der.</span><span class="sxs-lookup"><span data-stu-id="38433-105">e.g. Count.</span></span></param>
        <param name="currentValue"><span data-ttu-id="38433-106">Tatsächlichen Wert des Ressourcentyps.</span><span class="sxs-lookup"><span data-stu-id="38433-106">Actual value of the resource type.</span></span></param>
        <param name="limit"><span data-ttu-id="38433-107">Kontingent des Ressourcentyps.</span><span class="sxs-lookup"><span data-stu-id="38433-107">Quota of the resource type.</span></span></param>
        <summary>
            <span data-ttu-id="38433-108">Initialisiert eine neue Instanz der Klasse ResourceUsage.</span><span class="sxs-lookup"><span data-stu-id="38433-108">Initializes a new instance of the ResourceUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38433-109">Ruft ab, oder legt ihn fest Istwert des Ressourcentyps.</span><span class="sxs-lookup"><span data-stu-id="38433-109">Gets or sets actual value of the resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38433-110">Ruft ab, oder legt ihn fest Kontingent des Ressourcentyps.</span><span class="sxs-lookup"><span data-stu-id="38433-110">Gets or sets quota of the resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38433-111">Ruft ab, oder legt ihn fest Ressourcentyp der Verwendungen.</span><span class="sxs-lookup"><span data-stu-id="38433-111">Gets or sets resource type of the usages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="38433-112">Ruft ab, oder legt ihn fest Einheit der Verwendung.</span><span class="sxs-lookup"><span data-stu-id="38433-112">Gets or sets unit of the usage.</span></span> <span data-ttu-id="38433-113">z. B. die Anzahl der.</span><span class="sxs-lookup"><span data-stu-id="38433-113">e.g. Count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>