<Type Name="CheckNameAvailabilityOutput" FullName="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityOutput" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityOutput extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityOutput" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityOutput = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Überprüfen der Verfügbarkeit des Name-API-Ausgabe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityOutput ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CheckNameAvailabilityOutput-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityOutput (Nullable&lt;bool&gt; isNameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; isNameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional isNameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput" Usage="new Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput (isNameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isNameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isNameAvailable">Ein Wert, der angibt, ob der Name verfügbar ist.</param>
        <param name="reason">Der Grund, warum der Name nicht verfügbar ist.
            "Ungültig" gibt an, dass der angegebene Name nicht den benennungsanforderungen (falsche Länge, nicht unterstützte Zeichen usw.) übereinstimmt.
            "AlreadyExists" gibt an, dass der Name bereits verwendet wird und daher nicht verfügbar ist. Folgende Werte sind möglich: "Ungültig", "AlreadyExists"</param>
        <param name="message">Eine Meldung, die erklärt, warum der Name ist ungültig, und detaillierte benennungsanforderungen Ressource. Verfügbar nur, wenn "Ungültig" in der Eigenschaft "Reason" zurückgegeben.</param>
        <summary>
            Initialisiert eine neue Instanz der CheckNameAvailabilityOutput-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsNameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsNameAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsNameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.IsNameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsNameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsNameAvailable : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.IsNameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft einen Wert, der angibt, ob der Name verfügbar ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft eine Meldung, die erklärt, warum der Name ist ungültig, und detaillierte benennungsanforderungen Ressource ab. Verfügbar nur, wenn "Ungültig" in der Eigenschaft "Reason" zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string" Usage="Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Grund, warum der Name nicht verfügbar ist. "Ungültig" gibt an, dass der angegebene Name nicht den benennungsanforderungen (falsche Länge, nicht unterstützte Zeichen usw.) übereinstimmt. "AlreadyExists" gibt an, dass der Name bereits verwendet wird und daher nicht verfügbar ist. Folgende Werte sind möglich: "Ungültig", "AlreadyExists"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>