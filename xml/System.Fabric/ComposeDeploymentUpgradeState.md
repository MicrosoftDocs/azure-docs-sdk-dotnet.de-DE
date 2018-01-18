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
      <para><span data-ttu-id="529bf-101">Listet den Status des Upgrades Bereitstellung verfassen.</span><span class="sxs-lookup"><span data-stu-id="529bf-101">Enumerates the state of the compose deployment upgrade.</span></span></para>
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
          <para><span data-ttu-id="529bf-102">Gibt an, dass das Upgrade fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="529bf-102">Indicates that the upgrade has failed.</span></span></para>
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
          <para><span data-ttu-id="529bf-103">Gibt an, dass der Typ nicht gültig ist.</span><span class="sxs-lookup"><span data-stu-id="529bf-103">Indicates that the type is not valid.</span></span> <span data-ttu-id="529bf-104">Alle Service Fabric-Enumerationen haben einen ungültigen Typ.</span><span class="sxs-lookup"><span data-stu-id="529bf-104">All Service Fabric enumerations have an invalid type.</span></span></para>
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
          <para><span data-ttu-id="529bf-105">Gibt an, dass die Anwendung vom Typ des Ziels Bereitstellung verfassen werden bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="529bf-105">Indicates that the application type of the target compose deployment is being provisioned.</span></span></para>
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
          <para><span data-ttu-id="529bf-106">Gibt an, dass das Rollback des Upgrades abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="529bf-106">Indicates that the roll back of the upgrade is completed.</span></span> <span data-ttu-id="529bf-107">Das abgeschlossene Rollback gibt an, dass das Upgrade auf das Ziel fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="529bf-107">The completed rollback indicates that upgrade to the target version has failed.</span></span></para>
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
          <para><span data-ttu-id="529bf-108">Gibt an, dass das Upgrade gerade ein Rollback.</span><span class="sxs-lookup"><span data-stu-id="529bf-108">Indicates that the upgrade is in the process of rolling back.</span></span> <span data-ttu-id="529bf-109">Dies weist darauf hin, dass das Upgrade auf das Ziel verfassen Fehler bei der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="529bf-109">This indicates that upgrade to the target compose deployment has failed.</span></span> <span data-ttu-id="529bf-110">Beachten Sie, die diesem Zustand kann auch sein vorübergehend beobachtet werden, wenn das Upgrade unterbrochen wird, um ein neues Upgrade zu starten.</span><span class="sxs-lookup"><span data-stu-id="529bf-110">Note that this state can also be observed temporarily if the upgrade is interrupted to start a new upgrade.</span></span></para>
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
          <para><span data-ttu-id="529bf-111">Gibt an, dass das Upgrade auf das Ziel Bereitstellung verfassen abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="529bf-111">Indicates that the upgrade to the target compose deployment is completed.</span></span></para>
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
          <para><span data-ttu-id="529bf-112">Gibt an, dass das Upgrade auf das Ziel Bereitstellung verfassen werden ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="529bf-112">Indicates that the upgrade to the target compose deployment is in progress.</span></span></para>
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
          <para><span data-ttu-id="529bf-113">Gibt an, dass das Upgrade auf das Ziel Bereitstellung verfassen ist Benutzereingabe aussteht.</span><span class="sxs-lookup"><span data-stu-id="529bf-113">Indicates that the upgrade to the target compose deployment is pending user input.</span></span> <span data-ttu-id="529bf-114">Die <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> wird verwendet, um das Upgrade vorwärts zu bewegen.</span><span class="sxs-lookup"><span data-stu-id="529bf-114">The <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> is used to move the upgrade forward.</span></span></para>
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
          <para><span data-ttu-id="529bf-115">Gibt an, dass die Anwendung vom Typ der aktuellen Bereitstellung verfassen ist aufgehoben.%12%0 wird.</span><span class="sxs-lookup"><span data-stu-id="529bf-115">Indicates that the application type of the current compose deployment is being unprovisioned.</span></span></para>
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
          <para><span data-ttu-id="529bf-116">Gibt an, dass die Anwendung vom Typ des Ziels Bereitstellung verfassen ist aufgehoben.%12%0 wird.</span><span class="sxs-lookup"><span data-stu-id="529bf-116">Indicates that the application type of the target compose deployment is being unprovisioned.</span></span> <span data-ttu-id="529bf-117">Dieser Status Gibt an, Fehler bei der Aktualisierung und das Upgrade wird ein Rollback.</span><span class="sxs-lookup"><span data-stu-id="529bf-117">This state indicates the upgrade has failed and the upgrade is being rolled back.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>