<Type Name="AutoHealTriggers" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers">
  <TypeSignature Language="C#" Value="public class AutoHealTriggers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoHealTriggers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoHealTriggers" />
  <TypeSignature Language="F#" Value="type AutoHealTriggers = class" />
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
            <span data-ttu-id="2948a-101">Trigger Autom.</span><span class="sxs-lookup"><span data-stu-id="2948a-101">Triggers for auto-heal.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealTriggers ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2948a-102">Initialisiert eine neue Instanz der AutoHealTriggers-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2948a-102">Initializes a new instance of the AutoHealTriggers class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealTriggers (Microsoft.Azure.Management.AppService.Fluent.Models.RequestsBasedTrigger requests = null, Nullable&lt;int&gt; privateBytesInKB = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StatusCodesBasedTrigger&gt; statusCodes = null, Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger slowRequests = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.AppService.Fluent.Models.RequestsBasedTrigger requests, valuetype System.Nullable`1&lt;int32&gt; privateBytesInKB, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StatusCodesBasedTrigger&gt; statusCodes, class Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger slowRequests) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.#ctor(Microsoft.Azure.Management.AppService.Fluent.Models.RequestsBasedTrigger,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.StatusCodesBasedTrigger},Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional requests As RequestsBasedTrigger = null, Optional privateBytesInKB As Nullable(Of Integer) = null, Optional statusCodes As IList(Of StatusCodesBasedTrigger) = null, Optional slowRequests As SlowRequestsBasedTrigger = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers : Microsoft.Azure.Management.AppService.Fluent.Models.RequestsBasedTrigger * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StatusCodesBasedTrigger&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers (requests, privateBytesInKB, statusCodes, slowRequests)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requests" Type="Microsoft.Azure.Management.AppService.Fluent.Models.RequestsBasedTrigger" />
        <Parameter Name="privateBytesInKB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="statusCodes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StatusCodesBasedTrigger&gt;" />
        <Parameter Name="slowRequests" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger" />
      </Parameters>
      <Docs>
        <param name="requests"><span data-ttu-id="2948a-103">Eine Regel, die basierend auf die Gesamtzahl der Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="2948a-103">A rule based on total requests.</span></span></param>
        <param name="privateBytesInKB"><span data-ttu-id="2948a-104">Eine Regel, die basierend auf den privaten Bytes.</span><span class="sxs-lookup"><span data-stu-id="2948a-104">A rule based on private bytes.</span></span></param>
        <param name="statusCodes"><span data-ttu-id="2948a-105">Eine Regel auf Grundlage des Statuscodes.</span><span class="sxs-lookup"><span data-stu-id="2948a-105">A rule based on status codes.</span></span></param>
        <param name="slowRequests"><span data-ttu-id="2948a-106">Eine Regel, die basierend auf Anforderungsausführungszeit.</span><span class="sxs-lookup"><span data-stu-id="2948a-106">A rule based on request execution time.</span></span></param>
        <summary>
            <span data-ttu-id="2948a-107">Initialisiert eine neue Instanz der AutoHealTriggers-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2948a-107">Initializes a new instance of the AutoHealTriggers class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateBytesInKB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PrivateBytesInKB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PrivateBytesInKB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.PrivateBytesInKB" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateBytesInKB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PrivateBytesInKB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.PrivateBytesInKB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="privateBytesInKB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2948a-108">Abrufen / definieren eine Regel, die basierend auf den privaten Bytes.</span><span class="sxs-lookup"><span data-stu-id="2948a-108">Gets or sets a rule based on private bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Requests">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.RequestsBasedTrigger Requests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.RequestsBasedTrigger Requests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.Requests" />
      <MemberSignature Language="VB.NET" Value="Public Property Requests As RequestsBasedTrigger" />
      <MemberSignature Language="F#" Value="member this.Requests : Microsoft.Azure.Management.AppService.Fluent.Models.RequestsBasedTrigger with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.Requests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requests")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.RequestsBasedTrigger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2948a-109">Abrufen oder festlegen eine Regel basierend auf die Gesamtzahl der Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="2948a-109">Gets or sets a rule based on total requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SlowRequests">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger SlowRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger SlowRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.SlowRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property SlowRequests As SlowRequestsBasedTrigger" />
      <MemberSignature Language="F#" Value="member this.SlowRequests : Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.SlowRequests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="slowRequests")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2948a-110">Abrufen / definieren eine Regel basierend auf Anforderungsausführungszeit.</span><span class="sxs-lookup"><span data-stu-id="2948a-110">Gets or sets a rule based on request execution time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StatusCodesBasedTrigger&gt; StatusCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StatusCodesBasedTrigger&gt; StatusCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.StatusCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCodes As IList(Of StatusCodesBasedTrigger)" />
      <MemberSignature Language="F#" Value="member this.StatusCodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StatusCodesBasedTrigger&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers.StatusCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StatusCodesBasedTrigger&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2948a-111">Abrufen / definieren eine Regel basierend auf Statuscodes.</span><span class="sxs-lookup"><span data-stu-id="2948a-111">Gets or sets a rule based on status codes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>