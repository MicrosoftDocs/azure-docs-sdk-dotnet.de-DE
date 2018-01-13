<Type Name="MobileServicePushFailedException" FullName="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException">
  <TypeSignature Language="C#" Value="public class MobileServicePushFailedException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServicePushFailedException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServicePushFailedException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type MobileServicePushFailedException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Ausnahme ausgelöst, wenn die Clientpushinstallation nicht erfolgreich abgeschlossen wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServicePushFailedException (Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult pushResult, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult pushResult, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException.#ctor(Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (pushResult As MobileServicePushCompletionResult, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException : Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult * Exception -&gt; Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException" Usage="new Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException (pushResult, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pushResult" Type="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="pushResult">Ergebnis des Push-Vorgang.</param>
        <param name="innerException">Innere Ausnahme, die den Push fehlschlagen verursacht hat.</param>
        <summary>
            Initialisiert eine neue Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException" />.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PushResult">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult PushResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult PushResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException.PushResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PushResult As MobileServicePushCompletionResult" />
      <MemberSignature Language="F#" Value="member this.PushResult : Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushFailedException.PushResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ergebnis der Push-Vorgang
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>