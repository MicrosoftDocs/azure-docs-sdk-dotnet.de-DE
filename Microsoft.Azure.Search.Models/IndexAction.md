<Type Name="IndexAction" FullName="Microsoft.Azure.Search.Models.IndexAction">
  <TypeSignature Language="C#" Value="public class IndexAction : Microsoft.Azure.Search.Models.IndexActionBase&lt;Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexAction extends Microsoft.Azure.Search.Models.IndexActionBase`1&lt;class Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexAction" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexAction&#xA;Inherits IndexActionBase(Of Document)" />
  <TypeSignature Language="F#" Value="type IndexAction = class&#xA;    inherit IndexActionBase&lt;Document&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.IndexActionBase&lt;Microsoft.Azure.Search.Models.Document&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.Document</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Index-Aktion, die für ein Dokument ausgeführt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Delete (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Delete(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Delete(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Delete document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document">Das zu löschende Dokument; Felder als die Schlüssel werden ignoriert.</param>
        <summary>
            Erstellt eine neue IndexAction für das Löschen eines Dokuments an.
            </summary>
        <returns>Eine neue IndexAction.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Delete (string keyName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Delete(string keyName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Delete(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (keyName As String, keyValue As String) As IndexAction" />
      <MemberSignature Language="F#" Value="static member Delete : string * string -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Delete (keyName, keyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Name des Schlüsselfelds des Indexes.</param>
        <param name="keyValue">Der Schlüssel des Dokuments zu löschen.</param>
        <summary>
            Erstellt eine neue IndexAction für das Löschen eines Dokuments an.
            </summary>
        <returns>Eine neue IndexAction.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; Delete&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; Delete&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Delete``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member Delete : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.Delete document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="document">Das zu löschende Dokument; Felder als die Schlüssel werden ignoriert.</param>
        <summary>
            Erstellt eine neue IndexAction für das Löschen eines Dokuments an.
            </summary>
        <returns>Eine neue IndexAction.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Merge (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Merge(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Merge(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member Merge : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Merge document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document">Das Dokument zum Zusammenführen; Legen Sie nur die Felder, die Sie ändern möchten.</param>
        <summary>
            Erstellt eine neue IndexAction für das Zusammenführen ein Dokument in ein vorhandenes Dokument im Index.
            </summary>
        <returns>Eine neue IndexAction.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; Merge&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; Merge&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Merge``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member Merge : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.Merge document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="document">Das Dokument zum Zusammenführen; Legen Sie nur die Eigenschaften, die Sie ändern möchten.</param>
        <summary>
            Erstellt eine neue IndexAction für das Zusammenführen ein Dokument in ein vorhandenes Dokument im Index.
            </summary>
        <returns>Eine neue IndexAction.</returns>
        <remarks>
            Wenn Typ T NULL-Wert typisierte Eigenschaften enthält, können diese Eigenschaften nicht ordnungsgemäß zusammengeführt. Wenn Sie eine solche Eigenschaft nicht festgelegt, dauert es automatisch den Standardwert (z. B. 0 für Int) oder "false" für Bool, der den Wert der Eigenschaft, die derzeit im Index gespeicherten außer Kraft setzt, auch wenn dies nicht Ihre Absicht war. Aus diesem Grund wird dringend empfohlen, dass immer Deklarieren von Eigenschaften Wert eingegeben haben, um den Typ t auf NULL festgelegt werden
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction MergeOrUpload (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction MergeOrUpload(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document">Das Dokument, merge oder hochladen.</param>
        <summary>
            Erstellt eine neue IndexAction für Hochladen eines Dokuments, die dem Index oder in einem vorhandenen Dokument zusammenführen, wenn sie bereits im Index vorhanden ist.
            </summary>
        <returns>Eine neue IndexAction.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; MergeOrUpload&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; MergeOrUpload&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MergeOrUpload(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="document">Das Dokument, merge oder hochladen.</param>
        <summary>
            Erstellt eine neue IndexAction für Hochladen eines Dokuments, die dem Index oder in einem vorhandenen Dokument zusammenführen, wenn sie bereits im Index vorhanden ist.
            </summary>
        <returns>Eine neue IndexAction.</returns>
        <remarks>
            Wenn Typ T NULL-Wert typisierte Eigenschaften enthält, können diese Eigenschaften nicht ordnungsgemäß zusammengeführt. Wenn Sie eine solche Eigenschaft nicht festgelegt, dauert es automatisch den Standardwert (z. B. 0 für Int) oder "false" für Bool, der den Wert der Eigenschaft, die derzeit im Index gespeicherten außer Kraft setzt, auch wenn dies nicht Ihre Absicht war. Aus diesem Grund wird dringend empfohlen, dass immer Deklarieren von Eigenschaften Wert eingegeben haben, um den Typ t auf NULL festgelegt werden
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Upload (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Upload(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Upload(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member Upload : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Upload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document">Das Dokument hochladen.</param>
        <summary>
            Erstellt eine neue IndexAction zum Hochladen eines Dokuments, die dem Index.
            </summary>
        <returns>Eine neue IndexAction.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; Upload&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; Upload&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Upload``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Upload(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member Upload : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.Upload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="document">Das Dokument hochladen.</param>
        <summary>
            Erstellt eine neue IndexAction zum Hochladen eines Dokuments, die dem Index.
            </summary>
        <returns>Eine neue IndexAction.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>