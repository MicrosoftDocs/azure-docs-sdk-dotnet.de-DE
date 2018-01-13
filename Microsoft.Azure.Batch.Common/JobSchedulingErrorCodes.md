<Type Name="JobSchedulingErrorCodes" FullName="Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes">
  <TypeSignature Language="C#" Value="public static class JobSchedulingErrorCodes" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobSchedulingErrorCodes extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSchedulingErrorCodes" />
  <TypeSignature Language="F#" Value="type JobSchedulingErrorCodes = class" />
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
            Enthält die Fehlercodes, die spezifisch für die auftragsplanung Fehler.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoPoolCreationFailedWithQuotaReached">
      <MemberSignature Language="C#" Value="public const string AutoPoolCreationFailedWithQuotaReached;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AutoPoolCreationFailedWithQuotaReached" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.AutoPoolCreationFailedWithQuotaReached" />
      <MemberSignature Language="VB.NET" Value="Public Const AutoPoolCreationFailedWithQuotaReached As String " />
      <MemberSignature Language="F#" Value="val mutable AutoPoolCreationFailedWithQuotaReached : string" Usage="Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.AutoPoolCreationFailedWithQuotaReached" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Einen automatischer Pool zum Ausführen des Auftrags auf, konnte von der Batch-Dienst nicht erstellt werden, weil das Konto hat sein Kontingent von Compute-Knoten erreicht.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvalidApplicationPackageReferencesInAutoPool">
      <MemberSignature Language="C#" Value="public const string InvalidApplicationPackageReferencesInAutoPool;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string InvalidApplicationPackageReferencesInAutoPool" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.InvalidApplicationPackageReferencesInAutoPool" />
      <MemberSignature Language="VB.NET" Value="Public Const InvalidApplicationPackageReferencesInAutoPool As String " />
      <MemberSignature Language="F#" Value="val mutable InvalidApplicationPackageReferencesInAutoPool : string" Usage="Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.InvalidApplicationPackageReferencesInAutoPool" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Spezifikation des automatischen Pools für den Auftrag weist einen oder mehrere Anwendung Paket Verweise auf die nicht erfüllt werden konnte.  
            Dies tritt auf, der Anwendungs-Id oder die Version ist nicht vorhanden oder ist nicht aktiv, oder wenn der Verweis wurde eine Version angegeben, und es keine Standardversion konfiguriert ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvalidAutoScaleFormulaInAutoPool">
      <MemberSignature Language="C#" Value="public const string InvalidAutoScaleFormulaInAutoPool;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string InvalidAutoScaleFormulaInAutoPool" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.InvalidAutoScaleFormulaInAutoPool" />
      <MemberSignature Language="VB.NET" Value="Public Const InvalidAutoScaleFormulaInAutoPool As String " />
      <MemberSignature Language="F#" Value="val mutable InvalidAutoScaleFormulaInAutoPool : string" Usage="Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.InvalidAutoScaleFormulaInAutoPool" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Spezifikation des automatischen Pools für den Auftrag weist eine ungültige Formel für automatische Skalierung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvalidCertificatesInAutoPool">
      <MemberSignature Language="C#" Value="public const string InvalidCertificatesInAutoPool;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string InvalidCertificatesInAutoPool" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.InvalidCertificatesInAutoPool" />
      <MemberSignature Language="VB.NET" Value="Public Const InvalidCertificatesInAutoPool As String " />
      <MemberSignature Language="F#" Value="val mutable InvalidCertificatesInAutoPool : string" Usage="Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.InvalidCertificatesInAutoPool" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Spezifikation des automatischen Pools für den Auftrag wurde ein ungültiger Zertifikatsverweis (z. B. um ein Zertifikat, das nicht vorhanden ist).
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="public const string Unknown;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Unknown" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.Unknown" />
      <MemberSignature Language="VB.NET" Value="Public Const Unknown As String " />
      <MemberSignature Language="F#" Value="val mutable Unknown : string" Usage="Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Grund für die Planungsfehler ist unbekannt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>