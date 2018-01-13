<Type Name="NotifyDictionaryClearEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public class NotifyDictionaryClearEventArgs&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyDictionaryClearEventArgs`2&lt;TKey, TValue&gt; extends Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2&lt;!TKey, !TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyDictionaryClearEventArgs(Of TKey, TValue)&#xA;Inherits NotifyDictionaryChangedEventArgs(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TKey">TKey</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TValue">TValue</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TKey">Der Typ der Schlüssel in der <cref name="IReliableDictionary" />.</typeparam>
    <typeparam name="TValue">Der Typ der Werte in der <cref name="IReliableDictionary" />.</typeparam>
    <summary>
            Stellt Daten für das DictionaryChanged-Ereignis, das durch einen Löschvorgang verursacht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryClearEventArgs (long commitSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 commitSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs`2.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (commitSequenceNumber As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt; : int64 -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt; commitSequenceNumber" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commitSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="commitSequenceNumber">
            Die Sequenznummer der Commit der Transaktion deaktiviert die<cref name="IReliableDictionary" /></param>
        <summary>
            Initialisiert eine neue Instanz der dem<cref name="NotifyDictionaryClearEventArgs" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitSequenceNumber">
      <MemberSignature Language="C#" Value="public long CommitSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CommitSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs`2.CommitSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CommitSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CommitSequenceNumber : int64" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt;.CommitSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Sequenznummer des Commit für den Vorgang, der Klartext gespeichert.
            </summary>
        <value>
            Sequence Number, an dem der Clear ein Commit ausgeführt wurde.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>