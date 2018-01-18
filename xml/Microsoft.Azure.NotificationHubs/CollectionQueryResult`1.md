<Type Name="CollectionQueryResult&lt;T&gt;" FullName="Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;T&gt;">
  <TypeSignature Language="C#" Value="public sealed class CollectionQueryResult&lt;T&gt; : System.Collections.Generic.IEnumerable&lt;T&gt; where T : EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CollectionQueryResult`1&lt;(class Microsoft.Azure.NotificationHubs.Messaging.EntityDescription) T&gt; extends System.Object implements class System.Collections.Generic.IEnumerable`1&lt;!T&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.CollectionQueryResult`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CollectionQueryResult(Of T)&#xA;Implements IEnumerable(Of T)" />
  <TypeSignature Language="F#" Value="type CollectionQueryResult&lt;'T (requires 'T :&gt; EntityDescription)&gt; = class&#xA;    interface seq&lt;'T (requires 'T :&gt; EntityDescription)&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.EntityDescription</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="a636e-101">Der Typ des Ergebnisses.</span><span class="sxs-lookup"><span data-stu-id="a636e-101">The type of the result.</span></span></typeparam>
    <summary><span data-ttu-id="a636e-102">Stellt eine Auflistung Abfrageergebnis dar.</span><span class="sxs-lookup"><span data-stu-id="a636e-102">Represents a collection query result.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.CollectionQueryResult`1.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string" Usage="Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.Messaging.EntityDescription)&gt;.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a636e-103">Ruft ab oder legt das Fortsetzungstoken zum Abrufen des nächsten Satz von Ergebnissen verwendet.</span><span class="sxs-lookup"><span data-stu-id="a636e-103">Gets or sets the continuation token to use to retrieve the next set of results.</span></span></summary>
        <value><span data-ttu-id="a636e-104">Das Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="a636e-104">The continuation token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;T&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;!T&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CollectionQueryResult`1.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.Messaging.EntityDescription)&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.Messaging.EntityDescription)&gt;" Usage="collectionQueryResult.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a636e-105">Gibt einen Enumerator zurück, der die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="a636e-105">Returns an enumerator that iterates through the collection.</span></span></summary>
        <returns><span data-ttu-id="a636e-106">Ein Enumerator, der die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="a636e-106">An enumerator that iterates through the collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.CollectionQueryResult`1.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a636e-107">Gibt einen Enumerator zurück, der die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="a636e-107">Returns an enumerator that iterates through the collection.</span></span></summary>
        <returns><span data-ttu-id="a636e-108">Ein Enumerator, der die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="a636e-108">An enumerator that iterates through the collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>