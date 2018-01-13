<Type Name="IAsyncEnumerator&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IAsyncEnumerator&lt;out T&gt; : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAsyncEnumerator`1&lt;+ T&gt; implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAsyncEnumerator(Of Out T)&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IAsyncEnumerator&lt;'T&gt; = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>Covariant</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">Der Typ der aufzulistenden Objekte.</typeparam>
    <summary>
            Asynchrone Enumerator.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Current">
      <MemberSignature Language="C#" Value="public T Current { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Current" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1.Current" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Current As T" />
      <MemberSignature Language="F#" Value="member this.Current : 'T" Usage="Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;'T&gt;.Current" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das aktuelle Element im Enumerator ab.
            </summary>
        <value>
            Aktuelle Element im Enumerator.
            </value>
        <remarks>To be added.</remarks>
        <remark>
            Nach dem Aufruf von <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1.MoveNextAsync(System.Threading.CancellationToken)" /> vergangen am Ende der Auflistung wird als nicht definiertes Verhalten betrachtet.
            </remark>
      </Docs>
    </Member>
    <Member MemberName="MoveNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; MoveNextAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; MoveNextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1.MoveNextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MoveNextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iAsyncEnumerator.MoveNextAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Setzt den Enumerator auf das nächste Element des Enumerators an.
            </summary>
        <returns>
            "true", wenn der Enumerator erfolgreich auf das nächste Element gesetzt wurde; "false", wenn der Enumerator das Ende der Auflistung überschritten hat.
             </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Die Sammlung wurde nach der Erstellung des Enumerators geändert.</exception>
      </Docs>
    </Member>
    <Member MemberName="Reset">
      <MemberSignature Language="C#" Value="public void Reset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Reset() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1.Reset" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reset ()" />
      <MemberSignature Language="F#" Value="abstract member Reset : unit -&gt; unit" Usage="iAsyncEnumerator.Reset " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Setzt den Enumerator auf seine anfängliche Position vor dem ersten Element in der Auflistung.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Die Sammlung wurde nach der Erstellung des Enumerators geändert.</exception>
      </Docs>
    </Member>
  </Members>
</Type>