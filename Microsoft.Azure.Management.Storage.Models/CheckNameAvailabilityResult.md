<Type Name="CheckNameAvailabilityResult" FullName="Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityResult" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Antwort des CheckNameAvailability-Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResult (Nullable&lt;bool&gt; nameAvailable = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt; reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Reason&gt; reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.#ctor(System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.Storage.Models.Reason},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As Nullable(Of Reason) = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult : Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt; * string -&gt; Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult" Usage="new Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt;" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable">Ruft einen booleschen Wert, der angibt, ob der Name für die Verwendung verfügbar ist. Bei "true", ist der Name verfügbar. Wenn "false" wird bereits der Name oder ist ungültig und kann nicht verwendet werden.</param>
        <param name="reason">Ruft den Grund, dass ein speicherkontoname nicht verwendet werden konnte. Der Grund-Element wird nur zurückgegeben, wenn NameAvailable auf "false" festgelegt ist. Folgende Werte sind möglich: "AccountNameInvalid", "AlreadyExists"</param>
        <param name="message">Ruft eine Fehlermeldung angezeigt, die den Wert für den Grund im Detail erläutert.</param>
        <summary>
            Initialisiert eine neue Instanz der CheckNameAvailabilityResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            Ruft eine Fehlermeldung angezeigt, die den Wert für den Grund im Detail erläutert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            Ruft einen booleschen Wert, der angibt, ob der Name für die Verwendung verfügbar ist. Bei "true", ist der Name verfügbar. Wenn "false" wird bereits der Name oder ist ungültig und kann nicht verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt; Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Reason&gt; Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As Nullable(Of Reason)" />
      <MemberSignature Language="F#" Value="member this.Reason : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt;" Usage="Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Reason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Grund, dass ein speicherkontoname nicht verwendet werden konnte. Der Grund-Element wird nur zurückgegeben, wenn NameAvailable auf "false" festgelegt ist. Folgende Werte sind möglich: "AccountNameInvalid", "AlreadyExists"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>