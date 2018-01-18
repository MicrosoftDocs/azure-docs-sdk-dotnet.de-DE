<Type Name="TestCommandStateFilter" FullName="System.Fabric.Query.TestCommandStateFilter">
  <TypeSignature Language="C#" Value="public enum TestCommandStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed TestCommandStateFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.TestCommandStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum TestCommandStateFilter" />
  <TypeSignature Language="F#" Value="type TestCommandStateFilter = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Dies wird beim Aufrufen von GetTestCommandStatusListAsync() verwendet und gibt der Filter auf die TestCommandState verwenden.    <span data-ttu-id="4b0a2-102">Mehrere Filterwerte können angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4b0a2-102">Multiple filter values may be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.TestCommandStateFilter All = int32(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.TestCommandStateFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 65535" Usage="System.Fabric.Query.TestCommandStateFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.TestCommandStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>65535</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b0a2-103">Gibt an, nicht dazu ist keine Filterung auf TestCommandState.</span><span class="sxs-lookup"><span data-stu-id="4b0a2-103">Indicates not to do any filtering on TestCommandState.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Cancelled">
      <MemberSignature Language="C#" Value="Cancelled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.TestCommandStateFilter Cancelled = int32(32)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.TestCommandStateFilter.Cancelled" />
      <MemberSignature Language="VB.NET" Value="Cancelled" />
      <MemberSignature Language="F#" Value="Cancelled = 32" Usage="System.Fabric.Query.TestCommandStateFilter.Cancelled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.TestCommandStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>32</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b0a2-104">Dieser Filter wählt abgebrochen Test Befehle.</span><span class="sxs-lookup"><span data-stu-id="4b0a2-104">This filter selects Cancelled test commands.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="CompletedSuccessfully">
      <MemberSignature Language="C#" Value="CompletedSuccessfully" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.TestCommandStateFilter CompletedSuccessfully = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.TestCommandStateFilter.CompletedSuccessfully" />
      <MemberSignature Language="VB.NET" Value="CompletedSuccessfully" />
      <MemberSignature Language="F#" Value="CompletedSuccessfully = 8" Usage="System.Fabric.Query.TestCommandStateFilter.CompletedSuccessfully" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.TestCommandStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b0a2-105">Dieser Filter wählt abgeschlossen Test Befehle.</span><span class="sxs-lookup"><span data-stu-id="4b0a2-105">This filter selects Completed test commands.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.TestCommandStateFilter Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.TestCommandStateFilter.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.Query.TestCommandStateFilter.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.TestCommandStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b0a2-106">Der Standardfilter.</span><span class="sxs-lookup"><span data-stu-id="4b0a2-106">The default filter.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.TestCommandStateFilter Failed = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.TestCommandStateFilter.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 16" Usage="System.Fabric.Query.TestCommandStateFilter.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.TestCommandStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b0a2-107">Dieser Filter wählt Fehler Test Befehle.</span><span class="sxs-lookup"><span data-stu-id="4b0a2-107">This filter selects Failed test commands.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ForceCancelled">
      <MemberSignature Language="C#" Value="ForceCancelled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.TestCommandStateFilter ForceCancelled = int32(64)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.TestCommandStateFilter.ForceCancelled" />
      <MemberSignature Language="VB.NET" Value="ForceCancelled" />
      <MemberSignature Language="F#" Value="ForceCancelled = 64" Usage="System.Fabric.Query.TestCommandStateFilter.ForceCancelled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.TestCommandStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>64</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b0a2-108">Dieser Filter wählt ForceCancelled Test Befehle aus.</span><span class="sxs-lookup"><span data-stu-id="4b0a2-108">This filter selects ForceCancelled test commands.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingBack">
      <MemberSignature Language="C#" Value="RollingBack" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.TestCommandStateFilter RollingBack = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.TestCommandStateFilter.RollingBack" />
      <MemberSignature Language="VB.NET" Value="RollingBack" />
      <MemberSignature Language="F#" Value="RollingBack = 2" Usage="System.Fabric.Query.TestCommandStateFilter.RollingBack" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.TestCommandStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b0a2-109">Dieser Filter wählt Rollback Test Befehle aus.</span><span class="sxs-lookup"><span data-stu-id="4b0a2-109">This filter selects RollingBack test commands.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.TestCommandStateFilter Running = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.TestCommandStateFilter.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 1" Usage="System.Fabric.Query.TestCommandStateFilter.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.TestCommandStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b0a2-110">Dieser Filter wählt Test-Befehle ausführen.</span><span class="sxs-lookup"><span data-stu-id="4b0a2-110">This filter selects Running test commands.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>