<Type Name="SystemNodeRepairAction" FullName="System.Fabric.Repair.SystemNodeRepairAction">
  <TypeSignature Language="C#" Value="public enum SystemNodeRepairAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SystemNodeRepairAction extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.SystemNodeRepairAction" />
  <TypeSignature Language="VB.NET" Value="Public Enum SystemNodeRepairAction" />
  <TypeSignature Language="F#" Value="type SystemNodeRepairAction = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="7591d-101">Gibt Knoten Reparaturaktionen für die das System einen integrierten Executor besitzt.</span><span class="sxs-lookup"><span data-stu-id="7591d-101">Specifies node repair actions for which the system has a built-in executor.</span></span></para>
      <para><span data-ttu-id="7591d-102">Dieser Typ unterstützt die Service Fabric-Plattform; Es ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="7591d-102">This type supports the Service Fabric platform; it is not meant to be used directly from your code.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FullReimage">
      <MemberSignature Language="C#" Value="FullReimage" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.SystemNodeRepairAction FullReimage = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.SystemNodeRepairAction.FullReimage" />
      <MemberSignature Language="VB.NET" Value="FullReimage" />
      <MemberSignature Language="F#" Value="FullReimage = 2" Usage="System.Fabric.Repair.SystemNodeRepairAction.FullReimage" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.SystemNodeRepairAction</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7591d-103">Reimaging alle Datenträger der Zielknoten, die alle auf den Knoten gespeicherte Daten zu zerstören.</span><span class="sxs-lookup"><span data-stu-id="7591d-103">Reimages all disk volumes of the target nodes, destroying all data stored on the nodes.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="Reboot" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.SystemNodeRepairAction Reboot = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.SystemNodeRepairAction.Reboot" />
      <MemberSignature Language="VB.NET" Value="Reboot" />
      <MemberSignature Language="F#" Value="Reboot = 0" Usage="System.Fabric.Repair.SystemNodeRepairAction.Reboot" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.SystemNodeRepairAction</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7591d-104">Startet das Betriebssystem der Zielknoten neu.</span><span class="sxs-lookup"><span data-stu-id="7591d-104">Reboots the OS of the target nodes.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReimageOS">
      <MemberSignature Language="C#" Value="ReimageOS" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.SystemNodeRepairAction ReimageOS = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.SystemNodeRepairAction.ReimageOS" />
      <MemberSignature Language="VB.NET" Value="ReimageOS" />
      <MemberSignature Language="F#" Value="ReimageOS = 1" Usage="System.Fabric.Repair.SystemNodeRepairAction.ReimageOS" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.SystemNodeRepairAction</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7591d-105">Reimaging das Betriebssystemvolume der Zielknoten.</span><span class="sxs-lookup"><span data-stu-id="7591d-105">Reimages the OS volume of the target nodes.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>