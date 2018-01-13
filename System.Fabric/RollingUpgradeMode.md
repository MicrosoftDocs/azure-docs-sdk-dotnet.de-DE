<Type Name="RollingUpgradeMode" FullName="System.Fabric.RollingUpgradeMode">
  <TypeSignature Language="C#" Value="public enum RollingUpgradeMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RollingUpgradeMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.RollingUpgradeMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum RollingUpgradeMode" />
  <TypeSignature Language="F#" Value="type RollingUpgradeMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt den Typ des paralleles Upgrade, bei der Aktualisierung einer Anwendungsinstanz oder -Cluster.</para>
    </summary>
    <remarks>
      <para>Weitere Informationen finden Sie unter Aktualisieren und Skalieren von Service Fabric-Cluster, und Aktualisieren einer Anwendung.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.RollingUpgradeMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Alle Service Fabric-Enumerationen reserviert Ungültiges Flag.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Monitored">
      <MemberSignature Language="C#" Value="Monitored" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode Monitored = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.Monitored" />
      <MemberSignature Language="VB.NET" Value="Monitored" />
      <MemberSignature Language="F#" Value="Monitored = 3" Usage="System.Fabric.RollingUpgradeMode.Monitored" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Upgrade überwacht und automatisch erfolgen soll.</para>
        </summary>
        <remarks>
          <para>Nach dem Upgrade einer upgradedomäne (UD) wird Service Fabric fahren Sie mit der nächsten UD zu aktualisieren, wenn die Integrität der UD und der Cluster die definierten Integritätsrichtlinien für, dass das Upgrade erfüllt. Andernfalls wird das gesamte Upgrade als fehlerhaft gekennzeichnet und wird der Fehler beim Aktualisieren der Aktion ausgeführt. Die Standardaktion Fehler ist die gesamte Aktualisierung zurücksetzen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmonitoredAuto">
      <MemberSignature Language="C#" Value="UnmonitoredAuto" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode UnmonitoredAuto = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.UnmonitoredAuto" />
      <MemberSignature Language="VB.NET" Value="UnmonitoredAuto" />
      <MemberSignature Language="F#" Value="UnmonitoredAuto = 1" Usage="System.Fabric.RollingUpgradeMode.UnmonitoredAuto" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Upgrade nicht überwacht und automatisch erfolgen soll.</para>
        </summary>
        <remarks>
          <para>In diesem Modus geht automatisch zur nächste upgradedomäne aktualisieren, bis alle upgradedomänen aktualisiert werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmonitoredManual">
      <MemberSignature Language="C#" Value="UnmonitoredManual" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode UnmonitoredManual = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.UnmonitoredManual" />
      <MemberSignature Language="VB.NET" Value="UnmonitoredManual" />
      <MemberSignature Language="F#" Value="UnmonitoredManual = 2" Usage="System.Fabric.RollingUpgradeMode.UnmonitoredManual" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Upgrade nicht überwacht und manuell erfolgen soll.</para>
        </summary>
        <remarks>
          <para>In diesem Modus muss der Administrator angewiesen, wechseln zur nächsten upgradedomäne (mithilfe der <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> oder <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress)" /> Methoden) und das Upgrade fortsetzen.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>