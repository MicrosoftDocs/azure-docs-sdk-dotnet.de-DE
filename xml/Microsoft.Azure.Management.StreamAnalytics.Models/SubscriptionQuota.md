<Type Name="SubscriptionQuota" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota">
  <TypeSignature Language="C#" Value="public class SubscriptionQuota : Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionQuota extends Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionQuota&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type SubscriptionQuota = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="88aef-101">Beschreibt den aktuellen Kontingent für das Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="88aef-101">Describes the current quota for the subscription.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionQuota ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="88aef-102">Initialisiert eine neue Instanz der SubscriptionQuota-Klasse.</span><span class="sxs-lookup"><span data-stu-id="88aef-102">Initializes a new instance of the SubscriptionQuota class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionQuota (string id = null, string name = null, string type = null, Nullable&lt;int&gt; maxCount = null, Nullable&lt;int&gt; currentCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;int32&gt; maxCount, valuetype System.Nullable`1&lt;int32&gt; currentCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional maxCount As Nullable(Of Integer) = null, Optional currentCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota : string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota (id, name, type, maxCount, currentCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="maxCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="88aef-103">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="88aef-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="88aef-104">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="88aef-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="88aef-105">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="88aef-105">Resource type</span></span></param>
        <param name="maxCount"><span data-ttu-id="88aef-106">Die maximale zulässige Verwendung dieser Ressource.</span><span class="sxs-lookup"><span data-stu-id="88aef-106">The max permitted usage of this resource.</span></span></param>
        <param name="currentCount"><span data-ttu-id="88aef-107">Die aktuelle Verwendung dieser Ressource.</span><span class="sxs-lookup"><span data-stu-id="88aef-107">The current usage of this resource.</span></span></param>
        <summary>
            <span data-ttu-id="88aef-108">Initialisiert eine neue Instanz der SubscriptionQuota-Klasse.</span><span class="sxs-lookup"><span data-stu-id="88aef-108">Initializes a new instance of the SubscriptionQuota class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota.CurrentCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota.CurrentCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88aef-109">Ruft die aktuelle Verwendung der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="88aef-109">Gets the current usage of this resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota.MaxCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.SubscriptionQuota.MaxCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="88aef-110">Ruft die maximale zulässige Verwendung dieser Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="88aef-110">Gets the max permitted usage of this resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>