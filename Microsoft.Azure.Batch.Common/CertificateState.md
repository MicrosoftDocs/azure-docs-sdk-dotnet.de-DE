<Type Name="CertificateState" FullName="Microsoft.Azure.Batch.Common.CertificateState">
  <TypeSignature Language="C#" Value="public enum CertificateState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CertificateState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.CertificateState" />
  <TypeSignature Language="VB.NET" Value="Public Enum CertificateState" />
  <TypeSignature Language="F#" Value="type CertificateState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Der Status eines Zertifikats
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.CertificateState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.CertificateState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Common.CertificateState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.CertificateState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Das Zertifikat ist für die Verwendung in Pools verfügbar.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="DeleteFailed">
      <MemberSignature Language="C#" Value="DeleteFailed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.CertificateState DeleteFailed = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />
      <MemberSignature Language="VB.NET" Value="DeleteFailed" />
      <MemberSignature Language="F#" Value="DeleteFailed = 2" Usage="Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.CertificateState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Der Benutzer hat angefordert, dass das Zertifikat gelöscht werden, jedoch hinzu, die Verweise auf das Zertifikat immer noch vorhanden sind oder auf einem oder mehreren Computeknoten weiterhin installiert ist.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.CertificateState Deleting = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 1" Usage="Microsoft.Azure.Batch.Common.CertificateState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.CertificateState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Der Benutzer fordert, dass das Zertifikat gelöscht werden, aber der Delete-Vorgang wurde noch nicht abgeschlossen. Sie können nicht auf das Zertifikat beim Erstellen oder Aktualisieren von Pools verweisen.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>