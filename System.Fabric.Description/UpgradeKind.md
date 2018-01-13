<Type Name="UpgradeKind" FullName="System.Fabric.Description.UpgradeKind">
  <TypeSignature Language="C#" Value="public enum UpgradeKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UpgradeKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UpgradeKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum UpgradeKind" />
  <TypeSignature Language="F#" Value="type UpgradeKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="125fc-101">Listet die möglichen Arten des Upgrades an.</span><span class="sxs-lookup"><span data-stu-id="125fc-101">Enumerates the possible kinds of upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.UpgradeKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.UpgradeKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.UpgradeKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradeKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="125fc-102">Gibt an, dass dies ein ungültiges Upgrade.</span><span class="sxs-lookup"><span data-stu-id="125fc-102">Indicates that this is an invalid upgrade.</span></span> <span data-ttu-id="125fc-103">Alle Service Fabric-Enumerationen haben Mitglied reservierte "Ungültig".</span><span class="sxs-lookup"><span data-stu-id="125fc-103">All Service Fabric enumerations have a reserved "Invalid" member.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rolling">
      <MemberSignature Language="C#" Value="Rolling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.UpgradeKind Rolling = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.UpgradeKind.Rolling" />
      <MemberSignature Language="VB.NET" Value="Rolling" />
      <MemberSignature Language="F#" Value="Rolling = 1" Usage="System.Fabric.Description.UpgradeKind.Rolling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradeKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="125fc-104">Gibt an, dass dies ein paralleles Upgrade bildet.</span><span class="sxs-lookup"><span data-stu-id="125fc-104">Indicates that this is a rolling upgrade.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rolling_ForceRestart">
      <MemberSignature Language="C#" Value="Rolling_ForceRestart" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.UpgradeKind Rolling_ForceRestart = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.UpgradeKind.Rolling_ForceRestart" />
      <MemberSignature Language="VB.NET" Value="Rolling_ForceRestart" />
      <MemberSignature Language="F#" Value="Rolling_ForceRestart = 2" Usage="System.Fabric.Description.UpgradeKind.Rolling_ForceRestart" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradeKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="125fc-105">Gibt an, dass dies ein paralleles Upgrade und der Diensthost wird neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="125fc-105">Indicates that this is a rolling upgrade and the service host restarts.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rolling_NotificationOnly">
      <MemberSignature Language="C#" Value="Rolling_NotificationOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.UpgradeKind Rolling_NotificationOnly = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.UpgradeKind.Rolling_NotificationOnly" />
      <MemberSignature Language="VB.NET" Value="Rolling_NotificationOnly" />
      <MemberSignature Language="F#" Value="Rolling_NotificationOnly = 3" Usage="System.Fabric.Description.UpgradeKind.Rolling_NotificationOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradeKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="125fc-106">Gibt an, dass dies ein paralleles Upgrade ist und die Replikate nicht neu gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="125fc-106">Indicates that this is a rolling upgrade and replicas are not restarted.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>