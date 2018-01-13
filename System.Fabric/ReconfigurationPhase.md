<Type Name="ReconfigurationPhase" FullName="System.Fabric.ReconfigurationPhase">
  <TypeSignature Language="C#" Value="public enum ReconfigurationPhase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ReconfigurationPhase extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReconfigurationPhase" />
  <TypeSignature Language="VB.NET" Value="Public Enum ReconfigurationPhase" />
  <TypeSignature Language="F#" Value="type ReconfigurationPhase = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="3243b-101">Stellt die Replikat-Neukonfiguration-Phase dar.</span><span class="sxs-lookup"><span data-stu-id="3243b-101">Represents replica reconfiguration phase.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbortPhaseZero">
      <MemberSignature Language="C#" Value="AbortPhaseZero" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationPhase AbortPhaseZero = int32(7)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationPhase.AbortPhaseZero" />
      <MemberSignature Language="VB.NET" Value="AbortPhaseZero" />
      <MemberSignature Language="F#" Value="AbortPhaseZero = 7" Usage="System.Fabric.ReconfigurationPhase.AbortPhaseZero" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3243b-102">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="3243b-102">For internal use only.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationPhase None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationPhase.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.ReconfigurationPhase.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3243b-103">Es ist keine Neukonfiguration gleichzeitig in Verarbeitung befindlichen.</span><span class="sxs-lookup"><span data-stu-id="3243b-103">There is no reconfiguration currently in progress.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Phase0">
      <MemberSignature Language="C#" Value="Phase0" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationPhase Phase0 = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationPhase.Phase0" />
      <MemberSignature Language="VB.NET" Value="Phase0" />
      <MemberSignature Language="F#" Value="Phase0 = 2" Usage="System.Fabric.ReconfigurationPhase.Phase0" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3243b-104">Eine Neukonfiguration ist der Übertragung von Daten vom vorherigen primären Server mit dem neuen primären Replikat.</span><span class="sxs-lookup"><span data-stu-id="3243b-104">The reconfiguration is transferring data from the previous primary to the new primary.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Phase1">
      <MemberSignature Language="C#" Value="Phase1" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationPhase Phase1 = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationPhase.Phase1" />
      <MemberSignature Language="VB.NET" Value="Phase1" />
      <MemberSignature Language="F#" Value="Phase1 = 3" Usage="System.Fabric.ReconfigurationPhase.Phase1" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3243b-105">Eine Neukonfiguration abfragt der Replikatgruppe zum Ermitteln des Status.</span><span class="sxs-lookup"><span data-stu-id="3243b-105">The reconfiguration is querying the replica set for the progress.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Phase2">
      <MemberSignature Language="C#" Value="Phase2" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationPhase Phase2 = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationPhase.Phase2" />
      <MemberSignature Language="VB.NET" Value="Phase2" />
      <MemberSignature Language="F#" Value="Phase2 = 4" Usage="System.Fabric.ReconfigurationPhase.Phase2" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3243b-106">Eine Neukonfiguration ist das sicherstellen, dass Daten aus dem aktuellen primären Replikat in einem Großteil der Replikatgruppe vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="3243b-106">The reconfiguration is ensuring that data from the current primary is present in a majority of the replica set.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Phase3">
      <MemberSignature Language="C#" Value="Phase3" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationPhase Phase3 = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationPhase.Phase3" />
      <MemberSignature Language="VB.NET" Value="Phase3" />
      <MemberSignature Language="F#" Value="Phase3 = 5" Usage="System.Fabric.ReconfigurationPhase.Phase3" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3243b-107">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="3243b-107">For internal use only.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Phase4">
      <MemberSignature Language="C#" Value="Phase4" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationPhase Phase4 = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationPhase.Phase4" />
      <MemberSignature Language="VB.NET" Value="Phase4" />
      <MemberSignature Language="F#" Value="Phase4 = 6" Usage="System.Fabric.ReconfigurationPhase.Phase4" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3243b-108">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="3243b-108">For internal use only.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationPhase Unknown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationPhase.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 0" Usage="System.Fabric.ReconfigurationPhase.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3243b-109">Ungültige Neukonfiguration Phase.</span><span class="sxs-lookup"><span data-stu-id="3243b-109">Invalid reconfiguration phase.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>