<Type Name="CheckNameAvailabilityResult" FullName="Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityResult" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="900ae-101">Das Ergebnis des Vorgangs CheckNameAvailability</span><span class="sxs-lookup"><span data-stu-id="900ae-101">The Result of the CheckNameAvailability operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="900ae-102">Initialisiert eine neue Instanz der CheckNameAvailabilityResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="900ae-102">Initializes a new instance of the CheckNameAvailabilityResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResult (string message = null, Nullable&lt;bool&gt; nameAvailable = null, Nullable&lt;Microsoft.Azure.Management.EventHub.Models.UnavailableReason&gt; reason = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Nullable`1&lt;bool&gt; nameAvailable, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.EventHub.Models.UnavailableReason&gt; reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult.#ctor(System.String,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.EventHub.Models.UnavailableReason})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional message As String = null, Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As Nullable(Of UnavailableReason) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult : string * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.EventHub.Models.UnavailableReason&gt; -&gt; Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult" Usage="new Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult (message, nameAvailable, reason)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.Nullable&lt;Microsoft.Azure.Management.EventHub.Models.UnavailableReason&gt;" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="900ae-103">Detaillierte Informationen über die Ursache, die dem Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="900ae-103">The detailed info regarding the reason associated with the Namespace.</span></span></param>
        <param name="nameAvailable"><span data-ttu-id="900ae-104">Wert gibt an, Namespace ist Verfügbarkeit "true", wenn der Namespace verfügbar ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="900ae-104">Value indicating Namespace is availability, true if the Namespace is available; otherwise, false.</span></span></param>
        <param name="reason"><span data-ttu-id="900ae-105">Der Grund nicht verfügbar sind, der einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="900ae-105">The reason for unavailability of a Namespace.</span></span>
            <span data-ttu-id="900ae-106">Folgende Werte sind möglich: 'None', 'InvalidName', 'SubscriptionIsDisabled', "NameInUse", "NameInLockdown", "TooManyNamespaceInCurrentSubscription"</span><span class="sxs-lookup"><span data-stu-id="900ae-106">Possible values include: 'None', 'InvalidName', 'SubscriptionIsDisabled', 'NameInUse', 'NameInLockdown', 'TooManyNamespaceInCurrentSubscription'</span></span></param>
        <summary>
            <span data-ttu-id="900ae-107">Initialisiert eine neue Instanz der CheckNameAvailabilityResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="900ae-107">Initializes a new instance of the CheckNameAvailabilityResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="900ae-108">Ruft detaillierte Informationen, die die Ursache der Namespace zugeordnet bezüglich.</span><span class="sxs-lookup"><span data-stu-id="900ae-108">Gets the detailed info regarding the reason associated with the Namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="900ae-109">Ruft ab, oder legt ihn fest, der angibt, dass Namespace Verfügbarkeit "true" ist, wenn der Namespace verfügbar ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="900ae-109">Gets or sets value indicating Namespace is availability, true if the Namespace is available; otherwise, false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.EventHub.Models.UnavailableReason&gt; Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.EventHub.Models.UnavailableReason&gt; Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As Nullable(Of UnavailableReason)" />
      <MemberSignature Language="F#" Value="member this.Reason : Nullable&lt;Microsoft.Azure.Management.EventHub.Models.UnavailableReason&gt; with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.EventHub.Models.UnavailableReason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="900ae-110">Abrufen oder festlegen den Grund nicht verfügbar sind, der einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="900ae-110">Gets or sets the reason for unavailability of a Namespace.</span></span> <span data-ttu-id="900ae-111">Folgende Werte sind möglich: 'None', 'InvalidName', 'SubscriptionIsDisabled', "NameInUse", "NameInLockdown", "TooManyNamespaceInCurrentSubscription"</span><span class="sxs-lookup"><span data-stu-id="900ae-111">Possible values include: 'None', 'InvalidName', 'SubscriptionIsDisabled', 'NameInUse', 'NameInLockdown', 'TooManyNamespaceInCurrentSubscription'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>