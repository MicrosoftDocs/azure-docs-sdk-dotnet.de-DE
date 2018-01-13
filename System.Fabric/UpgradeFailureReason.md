<Type Name="UpgradeFailureReason" FullName="System.Fabric.UpgradeFailureReason">
  <TypeSignature Language="C#" Value="public enum UpgradeFailureReason" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UpgradeFailureReason extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeFailureReason" />
  <TypeSignature Language="VB.NET" Value="Public Enum UpgradeFailureReason" />
  <TypeSignature Language="F#" Value="type UpgradeFailureReason = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            Beschreibt mögliche Ursachen für Upgrade an.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthCheck">
      <MemberSignature Language="C#" Value="HealthCheck" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureReason HealthCheck = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureReason.HealthCheck" />
      <MemberSignature Language="VB.NET" Value="HealthCheck" />
      <MemberSignature Language="F#" Value="HealthCheck = 2" Usage="System.Fabric.UpgradeFailureReason.HealthCheck" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureReason</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            Fehler bei der Aktualisierung aufgrund Systemdiagnosen.
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Interrupted">
      <MemberSignature Language="C#" Value="Interrupted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureReason Interrupted = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureReason.Interrupted" />
      <MemberSignature Language="VB.NET" Value="Interrupted" />
      <MemberSignature Language="F#" Value="Interrupted = 1" Usage="System.Fabric.UpgradeFailureReason.Interrupted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureReason</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            Die Aktualisierung wurde unterbrochen, oder manuell zurückgesetzt.
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureReason None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureReason.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.UpgradeFailureReason.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureReason</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>
            Es gibt keine Fehler bei der Aktualisierung.
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="OverallUpgradeTimeout">
      <MemberSignature Language="C#" Value="OverallUpgradeTimeout" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureReason OverallUpgradeTimeout = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureReason.OverallUpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="OverallUpgradeTimeout" />
      <MemberSignature Language="F#" Value="OverallUpgradeTimeout = 4" Usage="System.Fabric.UpgradeFailureReason.OverallUpgradeTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureReason</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>
            Der timeoutgesamtwert für das Upgrade ist abgelaufen.
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ProcessingFailure">
      <MemberSignature Language="C#" Value="ProcessingFailure" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureReason ProcessingFailure = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureReason.ProcessingFailure" />
      <MemberSignature Language="VB.NET" Value="ProcessingFailure" />
      <MemberSignature Language="F#" Value="ProcessingFailure = 5" Usage="System.Fabric.UpgradeFailureReason.ProcessingFailure" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureReason</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>
            Fehler bei der Aktualisierung aufgrund eines Verarbeitungsfehlers.
            Zum Beispiel: Fehler beim Prozess Standard/Dienste. Ausführliche Informationen finden Sie unter <see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeStatusDetails" />.
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="UpgradeDomainTimeout" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureReason UpgradeDomainTimeout = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureReason.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="UpgradeDomainTimeout" />
      <MemberSignature Language="F#" Value="UpgradeDomainTimeout = 3" Usage="System.Fabric.UpgradeFailureReason.UpgradeDomainTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureReason</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>
            Die upgradedomäne Timeout ist abgelaufen.
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>