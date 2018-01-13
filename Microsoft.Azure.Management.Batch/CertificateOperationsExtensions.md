<Type Name="CertificateOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificateOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificateOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificateOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificateOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für CertificateOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate BeginCreate (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate BeginCreate(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="parameters">
            Zusätzliche Parameter für die zertifikaterstellung.
            </param>
        <param name="ifMatch">
            Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren. Der Wert "*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist. Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen. Andere Werte werden ignoriert.
            </param>
        <summary>
            Erstellt ein neues Zertifikat in das angegebene Konto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;BeginCreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="parameters">
            Zusätzliche Parameter für die zertifikaterstellung.
            </param>
        <param name="ifMatch">
            Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren. Der Wert "*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist. Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen. Andere Werte werden ignoriert.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt ein neues Zertifikat in das angegebene Konto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders BeginDelete (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders BeginDelete(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As CertificateDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDelete (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <summary>
            Löscht das angegebene Zertifikat.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene Zertifikat.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletion">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate CancelDeletion (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate CancelDeletion(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletion(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CancelDeletion (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As Certificate" />
      <MemberSignature Language="F#" Value="static member CancelDeletion : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletion (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <summary>
            Bricht einen fehlerhaften Löschvorgang eines Zertifikats aus dem angegebenen Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie versuchen, löschen ein Zertifikat, das von einem Pool verwendet wird oder compute-Knoten, ändert den Status des Zertifikats in DeleteFailed aus. Wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten, können Sie diesen Vorgang verwenden, um den Status des Zertifikats erneut auf aktiv festzulegen. Wenn Sie das Zertifikat löschen möchten, müssen Sie nicht, diesen Vorgang auszuführen, nach dem fehlerhaften Löschvorgang. Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; CancelDeletionAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; CancelDeletionAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletionAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelDeletionAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletionAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;CancelDeletionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Bricht einen fehlerhaften Löschvorgang eines Zertifikats aus dem angegebenen Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie versuchen, löschen ein Zertifikat, das von einem Pool verwendet wird oder compute-Knoten, ändert den Status des Zertifikats in DeleteFailed aus. Wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten, können Sie diesen Vorgang verwenden, um den Status des Zertifikats erneut auf aktiv festzulegen. Wenn Sie das Zertifikat löschen möchten, müssen Sie nicht, diesen Vorgang auszuführen, nach dem fehlerhaften Löschvorgang. Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Create (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Create(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Create(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Create (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="parameters">
            Zusätzliche Parameter für die zertifikaterstellung.
            </param>
        <param name="ifMatch">
            Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren. Der Wert "*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist. Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen. Andere Werte werden ignoriert.
            </param>
        <summary>
            Erstellt ein neues Zertifikat in das angegebene Konto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; CreateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; CreateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="parameters">
            Zusätzliche Parameter für die zertifikaterstellung.
            </param>
        <param name="ifMatch">
            Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren. Der Wert "*" können verwendet werden, um die Operation angewendet werden, wenn das Zertifikat bereits vorhanden ist. Wenn nicht angegeben, wird dieser Vorgang immer angewendet werden.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um ein neues Zertifikat erstellt werden, sondern um zu verhindern, aktualisieren ein vorhandenes Zertifikat zu ermöglichen. Andere Werte werden ignoriert.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt ein neues Zertifikat in das angegebene Konto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders Delete (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders Delete(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As CertificateDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Delete (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <summary>
            Löscht das angegebene Zertifikat.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht das angegebene Zertifikat.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Get (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Get(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Get(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As Certificate" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Get (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <summary>
            Ruft Informationen über das angegebene Zertifikat ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; GetAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; GetAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über das angegebene Zertifikat ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccount (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccount(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccount(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccount (operations As ICertificateOperations, resourceGroupName As String, accountName As String, Optional maxresults As Nullable(Of Integer) = null, Optional select As String = null, Optional filter As String = null) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccount : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccount (operations, resourceGroupName, accountName, maxresults, select, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="maxresults">
            Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.
            </param>
        <param name="select">
            Durch Trennzeichen getrennte Liste von Eigenschaften, die zurückgegeben werden sollen. z. B. "Eigenschaften/ProvisioningState". Nur die ersten Ebene unter Eigenschaften Eigenschaften / zur Auswahl gültig sind.
            </param>
        <param name="filter">
            OData-Filterausdruck. Gültige Eigenschaften für die Filterung sind "Eigenschaften/ProvisioningState", "Eigenschaften/ProvisioningStateTransitionTime", "Name".
            </param>
        <summary>
            Zeigt eine Liste aller Zertifikate in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * Nullable&lt;int&gt; * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountAsync (operations, resourceGroupName, accountName, maxresults, select, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;ListByBatchAccountAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="maxresults">
            Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.
            </param>
        <param name="select">
            Durch Trennzeichen getrennte Liste von Eigenschaften, die zurückgegeben werden sollen. z. B. "Eigenschaften/ProvisioningState". Nur die ersten Ebene unter Eigenschaften Eigenschaften / zur Auswahl gültig sind.
            </param>
        <param name="filter">
            OData-Filterausdruck. Gültige Eigenschaften für die Filterung sind "Eigenschaften/ProvisioningState", "Eigenschaften/ProvisioningStateTransitionTime", "Name".
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Zertifikate in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccountNext (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccountNext(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNext(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccountNext (operations As ICertificateOperations, nextPageLink As String) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNext : Microsoft.Azure.Management.Batch.ICertificateOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Zeigt eine Liste aller Zertifikate in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountNextAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountNextAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNextAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNextAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;ListByBatchAccountNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Zertifikate in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Update (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Update(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Update(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Update (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="parameters">
            Das Zertifikat zu aktualisierenden Entität.
            </param>
        <param name="ifMatch">
            Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren. Dieser Wert ausgelassen oder auf festgelegt werden kann "*" um den Vorgang ohne Bedingung anzuwenden.
            </param>
        <summary>
            Aktualisiert die Eigenschaften eines vorhandenen Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="certificateName">
            Der Bezeichner für das Zertifikat. Dies muss der Algorithmus und Fingerabdruck getrennt durch einen Bindestrich bestehen und muss die Daten in der Anforderung entsprechen. Z. B. SHA1-a3d1c5.
            </param>
        <param name="parameters">
            Das Zertifikat zu aktualisierenden Entität.
            </param>
        <param name="ifMatch">
            Die entitätszustandsversion (ETag) das Zertifikat zu aktualisieren. Dieser Wert ausgelassen oder auf festgelegt werden kann "*" um den Vorgang ohne Bedingung anzuwenden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften eines vorhandenen Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>