<Type Name="TransformationsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TransformationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TransformationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TransformationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TransformationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für TransformationsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Transformation CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplace (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="transformation">
            Die Definition der Transformation, die zum Erstellen Sie eine neue Transformation oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="transformationName">
            Der Name der Transformation.
            </param>
        <param name="ifMatch">
            Das ETag der Transformation. Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um eine neue Transformation erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Transformation zu ermöglichen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <summary>
            Erstellt eine Transformation oder eine bereits vorhandene Transformation unter einem vorhandenen streaming Auftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplaceAsync (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="transformation">
            Die Definition der Transformation, die zum Erstellen Sie eine neue Transformation oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="transformationName">
            Der Name der Transformation.
            </param>
        <param name="ifMatch">
            Das ETag der Transformation. Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um eine neue Transformation erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Transformation zu ermöglichen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Transformation oder eine bereits vorhandene Transformation unter einem vorhandenen streaming Auftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Get (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Get(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITransformationsOperations, resourceGroupName As String, jobName As String, transformationName As String) As Transformation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Get (operations, resourceGroupName, jobName, transformationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="transformationName">
            Der Name der Transformation.
            </param>
        <summary>
            Ruft Details zu der angegebenen Transformation ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, transformationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="transformationName">
            Der Name der Transformation.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Details zu der angegebenen Transformation ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Update (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Update(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Update (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="transformation">
            Eine Transformationsobjekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in die vorhandene Transformation (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Transformation identisch bleibt und als Ergebnis dieser PATCH-Vorgang nicht geändert werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="transformationName">
            Der Name der Transformation.
            </param>
        <param name="ifMatch">
            Das ETag der Transformation. Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <summary>
            Aktualisiert eine vorhandene Transformation unter einem vorhandenen streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) eine Transformation ohne den Rest der Definition der Auftrag oder Transformation.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.UpdateAsync (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="transformation">
            Eine Transformationsobjekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in die vorhandene Transformation (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Transformation identisch bleibt und als Ergebnis dieser PATCH-Vorgang nicht geändert werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="transformationName">
            Der Name der Transformation.
            </param>
        <param name="ifMatch">
            Das ETag der Transformation. Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine vorhandene Transformation unter einem vorhandenen streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) eine Transformation ohne den Rest der Definition der Auftrag oder Transformation.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>