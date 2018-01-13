<Type Name="IndexBatch" FullName="Microsoft.Azure.Search.Models.IndexBatch">
  <TypeSignature Language="C#" Value="public class IndexBatch : Microsoft.Azure.Search.Models.IndexBatchBase&lt;Microsoft.Azure.Search.Models.IndexAction,Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexBatch extends Microsoft.Azure.Search.Models.IndexBatchBase`2&lt;class Microsoft.Azure.Search.Models.IndexAction, class Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexBatch" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexBatch&#xA;Inherits IndexBatchBase(Of IndexAction, Document)" />
  <TypeSignature Language="F#" Value="type IndexBatch = class&#xA;    inherit IndexBatchBase&lt;IndexAction, Document&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.IndexBatchBase&lt;Microsoft.Azure.Search.Models.IndexAction,Microsoft.Azure.Search.Models.Document&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TAction">Microsoft.Azure.Search.Models.IndexAction</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TDoc">Microsoft.Azure.Search.Models.Document</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält einen Batch von Dokument hochladen, Zusammenführen und/oder Delete-Vorgänge der Azure Search-Index an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&gt; actions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.IndexAction&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.IndexAction})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (actions As IEnumerable(Of IndexAction))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexBatch : seq&lt;Microsoft.Azure.Search.Models.IndexAction&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="new Microsoft.Azure.Search.Models.IndexBatch actions" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actions" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&gt;" />
      </Parameters>
      <Docs>
        <param name="actions">Die indexaktionen in den Batch aufgenommen werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der IndexBatch-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.Document&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.Document})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (documents As IEnumerable(Of Document)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member Delete : seq&lt;Microsoft.Azure.Search.Models.Document&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.Delete documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt;" />
      </Parameters>
      <Docs>
        <param name="documents">Die Dokumente zu löschen; Felder als die Schlüssel werden ignoriert.</param>
        <summary>
            Erstellt eine neue IndexBatch für das Löschen eines Batches von Dokumenten an.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch Delete (string keyName, System.Collections.Generic.IEnumerable&lt;string&gt; keyValues);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch Delete(string keyName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; keyValues) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Delete(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (keyName As String, keyValues As IEnumerable(Of String)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member Delete : string * seq&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.Delete (keyName, keyValues)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyValues" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Name des Schlüsselfelds, die Dokumente im Index eindeutig identifiziert.</param>
        <param name="keyValues">Die Schlüssel der Dokumente zu löschen.</param>
        <summary>
            Erstellt eine neue IndexBatch für das Löschen eines Batches von Dokumenten an.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; Delete&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;T&gt; documents) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; Delete&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;!!T&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Delete``1(System.Collections.Generic.IEnumerable{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete(Of T As Class) (documents As IEnumerable(Of T)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member Delete : seq&lt;'T (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.Delete documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="documents">Die Dokumente zu löschen; Felder als die Schlüssel werden ignoriert.</param>
        <summary>
            Erstellt eine neue IndexBatch für das Löschen eines Batches von Dokumenten an.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch Merge (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch Merge(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.Document&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Merge(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.Document})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge (documents As IEnumerable(Of Document)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member Merge : seq&lt;Microsoft.Azure.Search.Models.Document&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.Merge documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt;" />
      </Parameters>
      <Docs>
        <param name="documents">Die Dokumente zusammenführen; Legen Sie nur die Felder, die Sie ändern möchten.</param>
        <summary>
            Erstellt eine neue IndexBatch für das Zusammenführen von Dokumenten in vorhandenen Dokumente im Index.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; Merge&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;T&gt; documents) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; Merge&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;!!T&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Merge``1(System.Collections.Generic.IEnumerable{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge(Of T As Class) (documents As IEnumerable(Of T)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member Merge : seq&lt;'T (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.Merge documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="documents">Die Dokumente zusammenführen; Legen Sie nur die Eigenschaften, die Sie ändern möchten.</param>
        <summary>
            Erstellt eine neue IndexBatch für das Zusammenführen von Dokumenten in vorhandenen Dokumente im Index.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>
            Wenn Typ T NULL-Wert typisierte Eigenschaften enthält, können diese Eigenschaften nicht ordnungsgemäß zusammengeführt. Wenn Sie eine solche Eigenschaft nicht festgelegt, dauert es automatisch den Standardwert (z. B. 0 für Int) oder "false" für Bool, der den Wert der Eigenschaft, die derzeit im Index gespeicherten außer Kraft setzt, auch wenn dies nicht Ihre Absicht war. Aus diesem Grund wird dringend empfohlen, dass immer Deklarieren von Eigenschaften Wert eingegeben haben, um den Typ t auf NULL festgelegt werden
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch MergeOrUpload (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch MergeOrUpload(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.Document&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.MergeOrUpload(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.Document})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MergeOrUpload (documents As IEnumerable(Of Document)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : seq&lt;Microsoft.Azure.Search.Models.Document&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.MergeOrUpload documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt;" />
      </Parameters>
      <Docs>
        <param name="documents">Die Dokumente zusammenführen oder hochladen.</param>
        <summary>
            Erstellt eine neue IndexBatch für das Hochladen von Dokumenten, die dem Index oder in vorhandenen Dokumente zusammenführen für diejenigen, die bereits im Index vorhanden sein.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; MergeOrUpload&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;T&gt; documents) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; MergeOrUpload&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;!!T&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.MergeOrUpload``1(System.Collections.Generic.IEnumerable{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MergeOrUpload(Of T As Class) (documents As IEnumerable(Of T)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : seq&lt;'T (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.MergeOrUpload documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="documents">Die Dokumente zusammenführen oder hochladen.</param>
        <summary>
            Erstellt eine neue IndexBatch für das Hochladen von Dokumenten, die dem Index oder in vorhandenen Dokumente zusammenführen für diejenigen, die bereits im Index vorhanden sein.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>
            Wenn Typ T NULL-Wert typisierte Eigenschaften enthält, können diese Eigenschaften nicht ordnungsgemäß zusammengeführt. Wenn Sie eine solche Eigenschaft nicht festgelegt, dauert es automatisch den Standardwert (z. B. 0 für Int) oder "false" für Bool, der den Wert der Eigenschaft, die derzeit im Index gespeicherten außer Kraft setzt, auch wenn dies nicht Ihre Absicht war. Aus diesem Grund wird dringend empfohlen, dass immer Deklarieren von Eigenschaften Wert eingegeben haben, um den Typ t auf NULL festgelegt werden
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="New">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch New (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&gt; actions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch New(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.IndexAction&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.New(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.IndexAction})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function New (actions As IEnumerable(Of IndexAction)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member New : seq&lt;Microsoft.Azure.Search.Models.IndexAction&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.New actions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actions" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&gt;" />
      </Parameters>
      <Docs>
        <param name="actions">Die indexaktionen in den Batch aufgenommen werden soll.</param>
        <summary>
            Erstellt eine neue Instanz der Klasse IndexBatch an.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="New&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; New&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;&gt; actions) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; New&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt;&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.New``1(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.IndexAction{``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function New(Of T As Class) (actions As IEnumerable(Of IndexAction(Of T))) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member New : seq&lt;Microsoft.Azure.Search.Models.IndexAction&lt;'T&gt;&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.New actions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actions" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="actions">Die indexaktionen in den Batch aufgenommen werden soll.</param>
        <summary>
            Erstellt eine neue Instanz der Klasse IndexBatch an.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>
            Sie können diese Methode einen Schlüsselverweis verwenden, wenn Sie nicht explizit Ihrer Modellklasse wie ein Typparameter angeben möchten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch Upload (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch Upload(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.Document&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Upload(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.Document})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Upload (documents As IEnumerable(Of Document)) As IndexBatch" />
      <MemberSignature Language="F#" Value="static member Upload : seq&lt;Microsoft.Azure.Search.Models.Document&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="Microsoft.Azure.Search.Models.IndexBatch.Upload documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.Document&gt;" />
      </Parameters>
      <Docs>
        <param name="documents">Die Dokumente hochladen.</param>
        <summary>
            Erstellt eine neue IndexBatch für das Hochladen von Dokumenten, die dem Index.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; Upload&lt;T&gt; (System.Collections.Generic.IEnumerable&lt;T&gt; documents) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; Upload&lt;class T&gt;(class System.Collections.Generic.IEnumerable`1&lt;!!T&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch.Upload``1(System.Collections.Generic.IEnumerable{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Upload(Of T As Class) (documents As IEnumerable(Of T)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="static member Upload : seq&lt;'T (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexBatch.Upload documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IEnumerable&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="documents">Die Dokumente hochladen.</param>
        <summary>
            Erstellt eine neue IndexBatch für das Hochladen von Dokumenten, die dem Index.
            </summary>
        <returns>Eine neue IndexBatch.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>