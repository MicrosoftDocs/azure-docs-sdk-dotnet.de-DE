<Type Name="PagedEnumerableExtensions" FullName="Microsoft.Azure.Batch.PagedEnumerableExtensions">
  <TypeSignature Language="C#" Value="public static class PagedEnumerableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PagedEnumerableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PagedEnumerableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PagedEnumerableExtensions" />
  <TypeSignature Language="F#" Value="type PagedEnumerableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Satz statischer (Shared in Visual Basic) Methoden zum Arbeiten mit Sequenzen, die implementieren <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ForEachAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ForEachAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, Action&lt;T&gt; body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ForEachAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, class System.Action`1&lt;!!T&gt; body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Action{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForEachAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * Action&lt;'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync (source, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ForEachAsync&gt;d__2`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="body" Type="System.Action&lt;T&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source">Die <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> zu durchlaufen.</param>
        <param name="body">Der Delegat, führen Sie für jedes Element im <paramref name="source" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Führt eine Iteration durch eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> Sequenz Aufrufs eines synchronen Delegaten für jedes Element.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" /> , die der Iteration Vorgang darstellt. Die Aufgabe abgeschlossen ist, wenn die Iteration abgeschlossen ist.</returns>
        <remarks>Diese Methode verarbeitet Elemente sequenziell, nicht gleichzeitig.  D. h. Abschluss für jedes Element in der Sequenz, die-Methode des Delegaten vor der Verarbeitung des nächsten Elements.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForEachAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ForEachAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, Func&lt;T,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ForEachAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, class System.Func`3&lt;!!T, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Func{``0,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForEachAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * Func&lt;'T, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync (source, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ForEachAsync&gt;d__1`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="body" Type="System.Func&lt;T,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source">Die <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> zu durchlaufen.</param>
        <param name="body">Asynchrone Delegaten auszuführende für jedes Element im <paramref name="source" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Führt eine Iteration durch eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> Sequenz, die einen asynchronen Delegaten für jedes Element aufrufen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" /> , die der Iteration Vorgang darstellt. Die Aufgabe abgeschlossen ist, wenn die Iteration abgeschlossen ist.</returns>
        <remarks>Diese Methode verarbeitet Elemente sequenziell, nicht gleichzeitig.  D. h., wartet der asynchronen Delegaten für jedes Element in der Sequenz, die Methode vor der Verarbeitung des nächsten Elements auf.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForEachAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ForEachAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, Func&lt;T,System.Threading.Tasks.Task&gt; body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ForEachAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, class System.Func`2&lt;!!T, class System.Threading.Tasks.Task&gt; body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Func{``0,System.Threading.Tasks.Task},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForEachAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * Func&lt;'T, System.Threading.Tasks.Task&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync (source, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ForEachAsync&gt;d__0`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="body" Type="System.Func&lt;T,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source">Die <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> zu durchlaufen.</param>
        <param name="body">Asynchrone Delegaten auszuführende für jedes Element im <paramref name="source" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Führt eine Iteration durch eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> Sequenz, die einen asynchronen Delegaten für jedes Element aufrufen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" /> , die der Iteration Vorgang darstellt. Die Aufgabe abgeschlossen ist, wenn die Iteration abgeschlossen ist.</returns>
        <remarks>Diese Methode verarbeitet Elemente sequenziell, nicht gleichzeitig.  D. h., wartet der asynchronen Delegaten für jedes Element in der Sequenz, die Methode vor der Verarbeitung des nächsten Elements auf.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToListAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt; ToListAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;!!T&gt;&gt; ToListAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ToListAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ToListAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;'T&gt;&gt;" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ToListAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ToListAsync&gt;d__3`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source">Die <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> zum Erstellen einer Liste aus.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Erstellt ein <see cref="T:System.Collections.Generic.List`1" /> aus einem <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Element, das den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist eine <see cref="T:System.Collections.Generic.List`1" /> , die alle Elemente der Quellsequenz enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>