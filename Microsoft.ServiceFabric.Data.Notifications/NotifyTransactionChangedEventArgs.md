<Type Name="NotifyTransactionChangedEventArgs" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs">
  <TypeSignature Language="C#" Value="public class NotifyTransactionChangedEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyTransactionChangedEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyTransactionChangedEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type NotifyTransactionChangedEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Ereignisargumente für Transaktionen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyTransactionChangedEventArgs (Microsoft.ServiceFabric.Data.ITransaction transaction, Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.ITransaction transaction, valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.#ctor(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (transaction As ITransaction, action As NotifyTransactionChangedAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs (transaction, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transaction" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="action" Type="Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction" />
      </Parameters>
      <Docs>
        <param name="transaction">Eine Transaktion, die die Änderung verknüpft ist.</param>
        <param name="action">Der Typ der Benachrichtigung.</param>
        <summary>
            Initialisiert eine neue Instanz der dem<cref name="NotifyStateManagerSingleEntityChangedEventArgs" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As NotifyTransactionChangedAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Typ der Aktion, die für die das Ereignis erstellt wurde.
            </summary>
        <value>
            Der Typ der Benachrichtigung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transaction">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.ITransaction Transaction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Data.ITransaction Transaction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.Transaction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transaction As ITransaction" />
      <MemberSignature Language="F#" Value="member this.Transaction : Microsoft.ServiceFabric.Data.ITransaction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs.Transaction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Transaktion ab.
            </summary>
        <value>
            Die Transaktion, die dem Vorgang zugeordnet wird.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>