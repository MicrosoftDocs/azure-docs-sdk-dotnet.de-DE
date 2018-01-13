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
            Das Ergebnis des Vorgangs CheckNameAvailability
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
            Initialisiert eine neue Instanz der CheckNameAvailabilityResult-Klasse.
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
        <param name="message">Detaillierte Informationen über die Ursache, die dem Namespace zugeordnet.</param>
        <param name="nameAvailable">Wert gibt an, Namespace ist Verfügbarkeit "true", wenn der Namespace verfügbar ist. andernfalls "false".</param>
        <param name="reason">Der Grund nicht verfügbar sind, der einen Namespace.
            Folgende Werte sind möglich: 'None', 'InvalidName', 'SubscriptionIsDisabled', "NameInUse", "NameInLockdown", "TooManyNamespaceInCurrentSubscription"</param>
        <summary>
            Initialisiert eine neue Instanz der CheckNameAvailabilityResult-Klasse.
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
            Ruft detaillierte Informationen, die die Ursache der Namespace zugeordnet bezüglich.
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
            Ruft ab, oder legt ihn fest, der angibt, dass Namespace Verfügbarkeit "true" ist, wenn der Namespace verfügbar ist; andernfalls "false".
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
            Abrufen oder festlegen den Grund nicht verfügbar sind, der einen Namespace. Folgende Werte sind möglich: 'None', 'InvalidName', 'SubscriptionIsDisabled', "NameInUse", "NameInLockdown", "TooManyNamespaceInCurrentSubscription"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>