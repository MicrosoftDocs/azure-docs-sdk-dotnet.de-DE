<Type Name="IndexBatchBase&lt;TAction,TDoc&gt;" FullName="Microsoft.Azure.Search.Models.IndexBatchBase&lt;TAction,TDoc&gt;">
  <TypeSignature Language="C#" Value="public abstract class IndexBatchBase&lt;TAction,TDoc&gt; where TAction : IndexActionBase&lt;TDoc&gt; where TDoc : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit IndexBatchBase`2&lt;(class Microsoft.Azure.Search.Models.IndexActionBase`1&lt;!TDoc&gt;) TAction, class TDoc&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexBatchBase`2" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class IndexBatchBase(Of TAction, TDoc)" />
  <TypeSignature Language="F#" Value="type IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TAction">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.IndexActionBase&lt;TDoc&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TDoc">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TAction">
            Der Typ der Aktion, die im Batch enthalten sein. Muss von "indexactionbase" abgeleitet werden.
            </typeparam>
    <typeparam name="TDoc">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
    <summary>
            Abstrakte Basisklasse für Batches hochladen, Zusammenführen und/oder löschen-Aktionen zum Senden an den Azure Search-Index.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected IndexBatchBase (System.Collections.Generic.IEnumerable&lt;TAction&gt; actions);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;!TAction&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatchBase`2.#ctor(System.Collections.Generic.IEnumerable{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (actions As IEnumerable(Of TAction))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt; : seq&lt;'Action (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt;)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt;" Usage="new Microsoft.Azure.Search.Models.IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt; actions" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actions" Type="System.Collections.Generic.IEnumerable&lt;TAction&gt;" />
      </Parameters>
      <Docs>
        <param name="actions">Die indexaktionen in den Batch aufgenommen werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der "indexbatchbase"-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;TAction&gt; Actions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;!TAction&gt; Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexBatchBase`2.Actions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Actions As IEnumerable(Of TAction)" />
      <MemberSignature Language="F#" Value="member this.Actions : seq&lt;'Action (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt;)&gt;" Usage="Microsoft.Azure.Search.Models.IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt;.Actions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Sequenz von Aktionen im Batch.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>