<Type Name="CertificateOperations" FullName="Microsoft.Azure.Batch.CertificateOperations">
  <TypeSignature Language="C#" Value="public class CertificateOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type CertificateOperations = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Führt zertifikatbezogene Vorgänge auf Azure Batch-Konto.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelDeleteCertificate">
      <MemberSignature Language="C#" Value="public void CancelDeleteCertificate (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CancelDeleteCertificate(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificate(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CancelDeleteCertificate (thumbprintAlgorithm As String, thumbprint As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteCertificate : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificateOperations.CancelDeleteCertificate (thumbprintAlgorithm, thumbprint, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter. Diese Angabe muss sha1.</param>
        <param name="thumbprint">Der Fingerabdruck des Zertifikats, das konnte nicht gelöscht werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</param>
        <summary>
            Bricht einen fehlerhaften Löschvorgang des angegebenen Zertifikats ab.  Dies kann erfolgen, wenn das Zertifikat verfügt die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> Status, und stellt das Zertifikat an die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> Zustand.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Wenn Sie weiterhin das Zertifikat (anstelle der Rückgabe an den aktiven) löschen möchten, müssen Sie nicht des fehlerhaften Löschvorgangs "Abbrechen". Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen (siehe <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelDeleteCertificateAsync (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelDeleteCertificateAsync(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteCertificateAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificateOperations.CancelDeleteCertificateAsync (thumbprintAlgorithm, thumbprint, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;CancelDeleteCertificateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter. Diese Angabe muss sha1.</param>
        <param name="thumbprint">Der Fingerabdruck des Zertifikats, das konnte nicht gelöscht werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Bricht einen fehlerhaften Löschvorgang des angegebenen Zertifikats ab.  Dies kann erfolgen, wenn das Zertifikat verfügt die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> Status, und stellt das Zertifikat an die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> Zustand.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Wenn Sie weiterhin das Zertifikat (anstelle der Rückgabe an den aktiven) löschen möchten, müssen Sie nicht des fehlerhaften Löschvorgangs "Abbrechen". Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen (siehe <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
          <para>Die "Abbrechen" gelöscht werden asynchron Vorgang ausgeführt wird.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (byte[] cerRawData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(unsigned int8[] cerRawData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (cerRawData As Byte()) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : byte[] -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate cerRawData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cerRawData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="cerRawData">Die Zertifikatdaten im CER-Format.</param>
        <summary>
            Erstellt ein neues <see cref="T:Microsoft.Azure.Batch.Certificate" /> aus Daten der CER-Format im Arbeitsspeicher.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> , ein neues Zertifikat, das nicht im Batch-Dienst hinzugefügt wurde darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (string cerFileName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(string cerFileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (cerFileName As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate cerFileName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cerFileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cerFileName">Der Pfad der CER-Datei.</param>
        <summary>
            Erstellt ein neues <see cref="T:Microsoft.Azure.Batch.Certificate" /> aus einer CER-Datei.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> , ein neues Zertifikat, das nicht im Batch-Dienst hinzugefügt wurde darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (byte[] pfxRawData, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(unsigned int8[] pfxRawData, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (pfxRawData As Byte(), password As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : byte[] * string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate (pfxRawData, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxRawData" Type="System.Byte[]" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxRawData">Die Zertifikatdaten im PFX-Format.</param>
        <param name="password">Das Kennwort für privaten Schlüssel des Zertifikats zugreifen.</param>
        <summary>
            Erstellt ein neues <see cref="T:Microsoft.Azure.Batch.Certificate" /> aus Daten der PFX-Format im Arbeitsspeicher.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> , ein neues Zertifikat, das nicht im Batch-Dienst hinzugefügt wurde darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (string pfxFileName, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(string pfxFileName, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (pfxFileName As String, password As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : string * string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate (pfxFileName, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFileName" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxFileName">Der Pfad zur PFX-Datei.</param>
        <param name="password">Das Kennwort für privaten Schlüssel des Zertifikats zugreifen.</param>
        <summary>
            Erstellt ein neues <see cref="T:Microsoft.Azure.Batch.Certificate" /> aus einer PFX-Datei.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> , ein neues Zertifikat, das nicht im Batch-Dienst hinzugefügt wurde darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.CertificateOperations" />.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</para>
          <para>Änderungen werden in der Reihenfolge der Auflistung angewendet. Der letzte write Wins.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificate">
      <MemberSignature Language="C#" Value="public void DeleteCertificate (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteCertificate(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificate(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteCertificate (thumbprintAlgorithm As String, thumbprint As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificate : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificateOperations.DeleteCertificate (thumbprintAlgorithm, thumbprint, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter. Diese Angabe muss sha1.</param>
        <param name="thumbprint">Der Fingerabdruck des Zertifikats zu löschen.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</param>
        <summary>
            Löscht das Zertifikat aus dem Batch-Konto an.
            </summary>
        <remarks>
          <para>Der Löschvorgang fordert an, dass das Zertifikat gelöscht werden.  Die Anforderung wird das Zertifikat abgelegt, der <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> Zustand.
            Der Batch-Dienst führt das tatsächliches Zertifikat löschen, ohne weitere Aktion des Clients.</para>
          <para>Ein Zertifikat kann nicht gelöscht werden, wenn eine Ressource (Pool oder Compute-Knoten) verwendet wird. Bevor Sie ein Zertifikat löschen können, müssen Sie daher sicherstellen, dass:</para>
          <list type="bullet">
            <item>
              <description>Das Zertifikat ist nicht für alle Pools zugeordnet.</description>
            </item>
            <item>
              <description>Das Zertifikat ist auf den Computeknoten nicht installiert.  (Auch wenn Sie ein Zertifikat aus einem Pool entfernen, ist es nicht entfernt, von vorhandenen Computeknoten in diesem Pool bis Neustart.)</description>
            </item>
          </list>
          <para>Wenn Sie versuchen, ein Zertifikat zu löschen, die verwendet wird, schlägt der Löschvorgang fehl. Die statusänderung des Zertifikats zu <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.
            Sie können <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> auf den Status wieder auf aktiv festlegen, wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteCertificateAsync (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteCertificateAsync(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificateOperations.DeleteCertificateAsync (thumbprintAlgorithm, thumbprint, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;DeleteCertificateAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter. Diese Angabe muss sha1.</param>
        <param name="thumbprint">Der Fingerabdruck des Zertifikats zu löschen.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Löscht das Zertifikat aus dem Batch-Konto an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Der Löschvorgang fordert an, dass das Zertifikat gelöscht werden.  Die Anforderung wird das Zertifikat abgelegt, der <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> Zustand.
            Der Batch-Dienst führt das tatsächliches Zertifikat löschen, ohne weitere Aktion des Clients.</para>
          <para>Ein Zertifikat kann nicht gelöscht werden, wenn eine Ressource (Pool oder Compute-Knoten) verwendet wird. Bevor Sie ein Zertifikat löschen können, müssen Sie daher sicherstellen, dass:</para>
          <list type="bullet">
            <item>
              <description>Das Zertifikat ist nicht für alle Pools zugeordnet.</description>
            </item>
            <item>
              <description>Das Zertifikat ist auf den Computeknoten nicht installiert.  (Auch wenn Sie ein Zertifikat aus einem Pool entfernen, ist es nicht entfernt, von vorhandenen Computeknoten in diesem Pool bis Neustart.)</description>
            </item>
          </list>
          <para>Wenn Sie versuchen, ein Zertifikat zu löschen, die verwendet wird, schlägt der Löschvorgang fehl. Die statusänderung des Zertifikats zu <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.
            Sie können <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> auf den Status wieder auf aktiv festlegen, wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten.</para>
          <para>Der Löschvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate GetCertificate (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate GetCertificate(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificate(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetCertificate : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.GetCertificate (thumbprintAlgorithm, thumbprint, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter. Diese Angabe muss sha1.</param>
        <param name="thumbprint">Der Fingerabdruck des Zertifikats zu erhalten.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.Certificate" /> ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> mit Informationen über das angegebene Zertifikat in das Azure Batch-Konto.</returns>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt; GetCertificateAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Certificate&gt; GetCertificateAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetCertificateAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt;" Usage="certificateOperations.GetCertificateAsync (thumbprintAlgorithm, thumbprint, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;GetCertificateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter. Diese Angabe muss sha1.</param>
        <param name="thumbprint">Der Fingerabdruck des Zertifikats zu erhalten.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.Certificate" /> ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> mit Informationen über das angegebene Zertifikat in das Azure Batch-Konto.</returns>
        <remarks>Der Abrufvorgang für das Zertifikat wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt; ListCertificates (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.Certificate&gt; ListCertificates(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.ListCertificates(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListCertificates : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt;" Usage="certificateOperations.ListCertificates (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die <see cref="T:Microsoft.Azure.Batch.Certificate">Zertifikate</see> in dem Batch-Konto.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die Zertifikate aufgelistet werden, synchron oder asynchron verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Zertifikate aus dem Batch-Dienst abgerufen.
            Datenabruf ist nicht atomaren; Zertifikate werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>