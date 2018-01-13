<Type Name="IPagedEnumerable&lt;T&gt;" FullName="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IPagedEnumerable&lt;T&gt; : System.Collections.Generic.IEnumerable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPagedEnumerable`1&lt;T&gt; implements class System.Collections.Generic.IEnumerable`1&lt;!T&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPagedEnumerable(Of T)&#xA;Implements IEnumerable(Of T)" />
  <TypeSignature Language="F#" Value="type IPagedEnumerable&lt;'T&gt; = interface&#xA;    interface seq&lt;'T&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">Der Typ der aufzulistenden Objekte.</typeparam>
    <summary>
            Macht Enumeratoren für eine ausgelagerte Sammlung an. Diese Enumeratoren unterstützen die einfache Iteration durch eine ausgelagerte Auflistung eines angegebenen Typs.
            
            Ausgelagerte Sammlungen werden durch einen oder mehrere Aufrufe an den Batch-Dienst unterstützt.  
            Jede dieser Aufrufe kann eine Variable Größe Seite mit Daten zurückgeben, die dann vom Enumerator verwendet wird. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetPagedEnumerator">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerator&lt;T&gt; GetPagedEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Batch.IPagedEnumerator`1&lt;!T&gt; GetPagedEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.IPagedEnumerable`1.GetPagedEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPagedEnumerator () As IPagedEnumerator(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetPagedEnumerator : unit -&gt; Microsoft.Azure.Batch.IPagedEnumerator&lt;'T&gt;" Usage="iPagedEnumerable.GetPagedEnumerator " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerator&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt einen asynchronen Enumerator, der die ausgelagerten Auflistung durchläuft.
            </summary>
        <returns>Der Typ der aufzulistenden Objekte.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>