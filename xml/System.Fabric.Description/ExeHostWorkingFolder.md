<Type Name="ExeHostWorkingFolder" FullName="System.Fabric.Description.ExeHostWorkingFolder">
  <TypeSignature Language="C#" Value="public enum ExeHostWorkingFolder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ExeHostWorkingFolder extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ExeHostWorkingFolder" />
  <TypeSignature Language="VB.NET" Value="Public Enum ExeHostWorkingFolder" />
  <TypeSignature Language="F#" Value="type ExeHostWorkingFolder = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="711c2-101">Listet die möglichen Start Ordnertypen.</span><span class="sxs-lookup"><span data-stu-id="711c2-101">Enumerates the possible start folder types.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CodeBase">
      <MemberSignature Language="C#" Value="CodeBase" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ExeHostWorkingFolder CodeBase = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ExeHostWorkingFolder.CodeBase" />
      <MemberSignature Language="VB.NET" Value="CodeBase" />
      <MemberSignature Language="F#" Value="CodeBase = 3" Usage="System.Fabric.Description.ExeHostWorkingFolder.CodeBase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ExeHostWorkingFolder</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="711c2-102">Gibt an, dass der Startordner ab dem die ausführbare Datei / Programm, das in der ExeHost angegeben ist, wird geladen.</span><span class="sxs-lookup"><span data-stu-id="711c2-102">Indicates that the start folder is from where the executable / program that is specified in the ExeHost is loaded.</span></span> <span data-ttu-id="711c2-103">Dieser Ordner kann aus dem Ordner Codepaket unterscheiden, wenn mehrere Ebenen in der Codepaket-Ordner vorhanden sind und ein angegebenes Programm von einem geschachtelten Ordnern ist.</span><span class="sxs-lookup"><span data-stu-id="711c2-103">This folder can differ from the Code Package folder if there are multiple levels in the Code Package folder and a specified program is from one of the nested folders.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="CodePackage">
      <MemberSignature Language="C#" Value="CodePackage" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ExeHostWorkingFolder CodePackage = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ExeHostWorkingFolder.CodePackage" />
      <MemberSignature Language="VB.NET" Value="CodePackage" />
      <MemberSignature Language="F#" Value="CodePackage = 2" Usage="System.Fabric.Description.ExeHostWorkingFolder.CodePackage" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ExeHostWorkingFolder</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="711c2-104">Gibt an, dass der Startordner das Codepaket-Ordner.</span><span class="sxs-lookup"><span data-stu-id="711c2-104">Indicates that the start folder is the Code Package’s folder.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ExeHostWorkingFolder Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ExeHostWorkingFolder.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.ExeHostWorkingFolder.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ExeHostWorkingFolder</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="711c2-105">Nicht verwenden.</span><span class="sxs-lookup"><span data-stu-id="711c2-105">Do not use.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Work">
      <MemberSignature Language="C#" Value="Work" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ExeHostWorkingFolder Work = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ExeHostWorkingFolder.Work" />
      <MemberSignature Language="VB.NET" Value="Work" />
      <MemberSignature Language="F#" Value="Work = 1" Usage="System.Fabric.Description.ExeHostWorkingFolder.Work" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ExeHostWorkingFolder</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="711c2-106">Gibt an, dass der Startordner Arbeitsordner für die Anwendung ist.</span><span class="sxs-lookup"><span data-stu-id="711c2-106">Indicates that the start folder is the application’s work folder.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>