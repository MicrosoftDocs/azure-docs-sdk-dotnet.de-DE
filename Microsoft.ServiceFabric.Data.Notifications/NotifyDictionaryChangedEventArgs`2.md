<Type Name="NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public abstract class NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt; : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NotifyDictionaryChangedEventArgs`2&lt;TKey, TValue&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NotifyDictionaryChangedEventArgs(Of TKey, TValue)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TKey">Der Typ der Schlüssel in der <cref name="IReliableDictionary" />.</typeparam>
    <typeparam name="TValue">Der Typ der Werte in der <cref name="IReliableDictionary" />.</typeparam>
    <summary>
            Stellt Daten für das DictionaryChanged-Ereignis.
            </summary>
    <remarks>
            DictionaryChanged Benachrichtigungen werden durch synchron ausgelöst <cref name="IReliableDictionary" /> als Teil der Anwendung des Vorgangs.
            Aufhält auf den Abschluss dieser Ereignisse kann dazu führen, dass das Replikat auf den Abschluss des Ereignisses blockiert wird.
            Es wird empfohlen, dass die Ereignisse so schnell wie möglich behandelt werden.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryChangedEventArgs (Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2.#ctor(Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (action As NotifyDictionaryChangedAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt; action" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="action" Type="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction" />
      </Parameters>
      <Docs>
        <param name="action">Der Typ der Benachrichtigung.</param>
        <summary>
            Initialisiert eine neue Instanz der dem<cref name="NotifyDictionaryChangedEventArgs" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As NotifyDictionaryChangedAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Aktion ab, die das Ereignis verursacht hat.
            </summary>
        <value>Der Typ der Benachrichtigung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>