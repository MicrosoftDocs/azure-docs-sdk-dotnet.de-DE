<Type Name="AuthorizationFailedException" FullName="Microsoft.ServiceBus.AuthorizationFailedException">
  <TypeSignature Language="C#" Value="public class AuthorizationFailedException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit AuthorizationFailedException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.AuthorizationFailedException" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthorizationFailedException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type AuthorizationFailedException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Die Ausnahme, die tritt auf, wenn eine Autorisierung fehlschlägt. </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.AuthorizationFailedException.FailureCode ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.AuthorizationFailedException/FailureCode ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.AuthorizationFailedException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As AuthorizationFailedException.FailureCode" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Microsoft.ServiceBus.AuthorizationFailedException.FailureCode" Usage="Microsoft.ServiceBus.AuthorizationFailedException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.AuthorizationFailedException+FailureCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder festlegen den Fehlercode, der die Ursache für Fehler bei der Autorisierung beschreibt.</summary>
        <value>Einer der Werte von der<see cref="T:Microsoft.ServiceBus.AuthorizationFailedException.FailureCode" /> Enumeration.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.AuthorizationFailedException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="authorizationFailedException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">Das mit Daten aufzufüllende <see cref="T:System.Runtime.Serialization.SerializationInfo" />-Objekt.</param>
        <param name="context">Das Ziel (siehe <see cref="T:System.Runtime.Serialization.StreamingContext" />) dieser Serialisierung.</param>
        <summary>Füllt ein <see cref="T:System.Runtime.Serialization.SerializationInfo" />-Objekt mit den Daten, die zum Serialisieren des Zielobjekts erforderlich sind.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>