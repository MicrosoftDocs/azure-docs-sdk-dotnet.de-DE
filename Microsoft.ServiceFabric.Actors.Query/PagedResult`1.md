<Type Name="PagedResult&lt;T&gt;" FullName="Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;T&gt;">
  <TypeSignature Language="C#" Value="public sealed class PagedResult&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PagedResult`1&lt;class T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Query.PagedResult`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PagedResult(Of T)" />
  <TypeSignature Language="F#" Value="type PagedResult&lt;'T (requires 'T : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="PagedResult", Namespace="urn:actors")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Collections.Generic.List`1&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T">
      <see cref="T:System.Type" />die Elemente enthält dieses Abfrageergebnis.</typeparam>
    <summary>
            Das Ergebnis des actoraufrufen, die Abfrage darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PagedResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Query.PagedResult`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.Query.PagedResult`1" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Query.ContinuationToken ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Query.ContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Query.PagedResult`1.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As ContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.ServiceFabric.Actors.Query.ContinuationToken with get, set" Usage="Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;'T (requires 'T : null)&gt;.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=false, Name="ContinuationToken", Order=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Query.ContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Fortsetzungstoken, der angibt, ob weitere Elemente abgerufen werden, indem Sie die Methode erneut aufrufen müssen.
            </summary>
        <value>ConinutationToken signalisieren If die Methode zurückgegeben, die <see cref="T:Microsoft.ServiceFabric.Actors.Query.PagedResult`1" /> muss erneut aufgerufen, um weitere Ergebnisse zu erhalten </value>
        <remarks>Fortsetzung token bedeutet, dass das Ergebnis aller Elemente und keine Aufrufe von Methode enthält ein null-Wert muss vorgenommen werden, um weitere Elemente abzurufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Items">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; Items { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; Items" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Query.PagedResult`1.Items" />
      <MemberSignature Language="VB.NET" Value="Public Property Items As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="member this.Items : seq&lt;'T (requires 'T : null)&gt; with get, set" Usage="Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;'T (requires 'T : null)&gt;.Items" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="Items", Order=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Enumerator zum Durchlaufen der Ergebnisse.
            </summary>
        <value>Ein Enumerator, der eine einfache Iteration durch die Auflistung unterstützt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>