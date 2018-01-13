<Type Name="ComposeDeploymentUpgradeState" FullName="System.Fabric.ComposeDeploymentUpgradeState">
  <TypeSignature Language="C#" Value="public enum ComposeDeploymentUpgradeState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComposeDeploymentUpgradeState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ComposeDeploymentUpgradeState" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComposeDeploymentUpgradeState" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentUpgradeState = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Listet den Status des Upgrades Bereitstellung verfassen.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState Failed = int32(9)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 9" Usage="System.Fabric.ComposeDeploymentUpgradeState.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>9</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Upgrade fehlgeschlagen ist.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.ComposeDeploymentUpgradeState.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Typ nicht gültig ist. Alle Service Fabric-Enumerationen haben einen ungültigen Typ.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningTarget">
      <MemberSignature Language="C#" Value="ProvisioningTarget" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState ProvisioningTarget = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.ProvisioningTarget" />
      <MemberSignature Language="VB.NET" Value="ProvisioningTarget" />
      <MemberSignature Language="F#" Value="ProvisioningTarget = 1" Usage="System.Fabric.ComposeDeploymentUpgradeState.ProvisioningTarget" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Anwendung vom Typ des Ziels Bereitstellung verfassen werden bereitgestellt.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingBackCompleted">
      <MemberSignature Language="C#" Value="RollingBackCompleted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingBackCompleted = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingBackCompleted" />
      <MemberSignature Language="VB.NET" Value="RollingBackCompleted" />
      <MemberSignature Language="F#" Value="RollingBackCompleted = 8" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingBackCompleted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Rollback des Upgrades abgeschlossen ist. Das abgeschlossene Rollback gibt an, dass das Upgrade auf das Ziel fehlgeschlagen ist.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingBackInProgress">
      <MemberSignature Language="C#" Value="RollingBackInProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingBackInProgress = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingBackInProgress" />
      <MemberSignature Language="VB.NET" Value="RollingBackInProgress" />
      <MemberSignature Language="F#" Value="RollingBackInProgress = 6" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingBackInProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Upgrade gerade ein Rollback. Dies weist darauf hin, dass das Upgrade auf das Ziel verfassen Fehler bei der Bereitstellung. Beachten Sie, die diesem Zustand kann auch sein vorübergehend beobachtet werden, wenn das Upgrade unterbrochen wird, um ein neues Upgrade zu starten.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingForwardCompleted">
      <MemberSignature Language="C#" Value="RollingForwardCompleted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingForwardCompleted = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingForwardCompleted" />
      <MemberSignature Language="VB.NET" Value="RollingForwardCompleted" />
      <MemberSignature Language="F#" Value="RollingForwardCompleted = 5" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingForwardCompleted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Upgrade auf das Ziel Bereitstellung verfassen abgeschlossen ist.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingForwardInProgress">
      <MemberSignature Language="C#" Value="RollingForwardInProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingForwardInProgress = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingForwardInProgress" />
      <MemberSignature Language="VB.NET" Value="RollingForwardInProgress" />
      <MemberSignature Language="F#" Value="RollingForwardInProgress = 2" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingForwardInProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Upgrade auf das Ziel Bereitstellung verfassen werden ausgeführt.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingForwardPending">
      <MemberSignature Language="C#" Value="RollingForwardPending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState RollingForwardPending = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.RollingForwardPending" />
      <MemberSignature Language="VB.NET" Value="RollingForwardPending" />
      <MemberSignature Language="F#" Value="RollingForwardPending = 3" Usage="System.Fabric.ComposeDeploymentUpgradeState.RollingForwardPending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass das Upgrade auf das Ziel Bereitstellung verfassen ist Benutzereingabe aussteht. Die <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> wird verwendet, um das Upgrade vorwärts zu bewegen.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="UnprovisioningCurrent">
      <MemberSignature Language="C#" Value="UnprovisioningCurrent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState UnprovisioningCurrent = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.UnprovisioningCurrent" />
      <MemberSignature Language="VB.NET" Value="UnprovisioningCurrent" />
      <MemberSignature Language="F#" Value="UnprovisioningCurrent = 4" Usage="System.Fabric.ComposeDeploymentUpgradeState.UnprovisioningCurrent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Anwendung vom Typ der aktuellen Bereitstellung verfassen ist aufgehoben.%12%0 wird.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="UnprovisioningTarget">
      <MemberSignature Language="C#" Value="UnprovisioningTarget" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ComposeDeploymentUpgradeState UnprovisioningTarget = int32(7)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ComposeDeploymentUpgradeState.UnprovisioningTarget" />
      <MemberSignature Language="VB.NET" Value="UnprovisioningTarget" />
      <MemberSignature Language="F#" Value="UnprovisioningTarget = 7" Usage="System.Fabric.ComposeDeploymentUpgradeState.UnprovisioningTarget" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Anwendung vom Typ des Ziels Bereitstellung verfassen ist aufgehoben.%12%0 wird. Dieser Status Gibt an, Fehler bei der Aktualisierung und das Upgrade wird ein Rollback.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>