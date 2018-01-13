<Type Name="MobileServicePushCompletionResult" FullName="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult">
  <TypeSignature Language="C#" Value="public class MobileServicePushCompletionResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServicePushCompletionResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServicePushCompletionResult" />
  <TypeSignature Language="F#" Value="type MobileServicePushCompletionResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Bietet Ihnen Fehler und Status der Clientpushinstallation abgeschlossen wurde.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServicePushCompletionResult (System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError&gt; errors, Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushStatus status);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError&gt; errors, valuetype Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushStatus status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult.#ctor(System.Collections.Generic.IEnumerable{Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError},Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errors As IEnumerable(Of MobileServiceTableOperationError), status As MobileServicePushStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult : seq&lt;Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError&gt; * Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushStatus -&gt; Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" Usage="new Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult (errors, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError&gt;" />
        <Parameter Name="status" Type="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushStatus" />
      </Parameters>
      <Docs>
        <param name="errors">Die Auflistung von Fehlern, die zur Ausführung des Vorgangs auf die Remotetabelle aufgetreten sind.</param>
        <param name="status">Der Status in die Clientpushinstallation abgeschlossen werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" />.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError&gt; Errors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult.Errors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Errors As ReadOnlyCollection(Of MobileServiceTableOperationError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError&gt;" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Fehler, die durch das Ausführen von Vorgang für die Remotetabelle hervorgerufen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As MobileServicePushStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushStatus" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Status in die Clientpushinstallation abgeschlossen werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>