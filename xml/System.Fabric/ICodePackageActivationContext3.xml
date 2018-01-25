<Type Name="ICodePackageActivationContext3" FullName="System.Fabric.ICodePackageActivationContext3">
  <TypeSignature Language="C#" Value="public interface ICodePackageActivationContext3 : IDisposable, System.Fabric.ICodePackageActivationContext2" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICodePackageActivationContext3 implements class System.Fabric.ICodePackageActivationContext, class System.Fabric.ICodePackageActivationContext2, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ICodePackageActivationContext3" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICodePackageActivationContext3&#xA;Implements ICodePackageActivationContext2, IDisposable" />
  <TypeSignature Language="F#" Value="type ICodePackageActivationContext3 = interface&#xA;    interface ICodePackageActivationContext2&#xA;    interface ICodePackageActivationContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.ICodePackageActivationContext2</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c18fc-101">Stellt Aktivierungskontext für die Fabric-Dienst aktiviert Service.</span><span class="sxs-lookup"><span data-stu-id="c18fc-101">Represents activation context for the Service Fabric activated service.</span></span>
            </summary>
    <remarks><span data-ttu-id="c18fc-102">Enthält Informationen über das Dienstmanifest sowie Informationen zu dem Paket derzeit aktivierten Code Geschäfts-Directory, die Kontext-Id usw.</span><span class="sxs-lookup"><span data-stu-id="c18fc-102">Includes information from the service manifest as well as information about the currently activated code package like work directory, context id etc.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDirectory">
      <MemberSignature Language="C#" Value="public string GetDirectory (string logicalDirectoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetDirectory(string logicalDirectoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext3.GetDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDirectory (logicalDirectoryName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member GetDirectory : string -&gt; string" Usage="iCodePackageActivationContext3.GetDirectory logicalDirectoryName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logicalDirectoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="logicalDirectoryName">To be added.</param>
        <summary>
            <span data-ttu-id="c18fc-103">Ruft den Pfad zum Unterverzeichnis im Arbeitsverzeichnis mit dem Namen "LogicalDirectoryName" ab.</span><span class="sxs-lookup"><span data-stu-id="c18fc-103">Retrieves the path to sub directory inside the work directory with the name "logicalDirectoryName".</span></span>
            </summary>
        <returns><span data-ttu-id="c18fc-104">Der Pfad zum Unterverzeichnis mit dem Namen LogicalDirectoryName im Arbeitsverzeichnis</span><span class="sxs-lookup"><span data-stu-id="c18fc-104">The path to sub directory with name logicalDirectoryName inside work directory</span></span></returns>
        <remarks><span data-ttu-id="c18fc-105">Löst eine Ausnahme aus, wenn LogicalDirectoryName Arbeit im Verzeichnis nicht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="c18fc-105">Throws an exception if logicalDirectoryName is not found under work directory.</span></span>
            <span data-ttu-id="c18fc-106">Andernfalls wird der Verzeichnispfad WorkDirectory\logicalDirectoryName zurückgegeben, die einen symbolischen Link mit mit Namen unter LogicalDirectories Abschnitt ClusterManifest angegebene Verzeichnis ist.</span><span class="sxs-lookup"><span data-stu-id="c18fc-106">Otherwise will return directory path WorkDirectory\logicalDirectoryName which is a symbolic link to directory specified with Name under LogicalDirectories Section of ClusterManifest.</span></span>
            <span data-ttu-id="c18fc-107">zum Beispiel: Wenn Sie angegeben haben <LogicalDirectory LogicalDirectoryName="Foo" MappedTo="D:\\Foo" /> und der Aufruf dieser Methode mit DirectoryName "Foo" wird zurückgegeben, Pfad WorkDirectory\Foo.</span><span class="sxs-lookup"><span data-stu-id="c18fc-107">for example: if you have specified <LogicalDirectory LogicalDirectoryName="Foo" MappedTo="D:\\Foo" /> and call to this method with directoryName "Foo" will return you path WorkDirectory\Foo.</span></span> <span data-ttu-id="c18fc-108">Versucht, Schreibvorgänge zurückgegeben, dass der Pfad zum D:\Foo\NodeId\ApplicationType_ApplicationVersion geleitet werden.</span><span class="sxs-lookup"><span data-stu-id="c18fc-108">Any writes made to returned path will go to D:\Foo\NodeId\ApplicationType_ApplicationVersion.</span></span>
            <span data-ttu-id="c18fc-109">Diese Methode ist Groß-/Kleinschreibung beachtet, daher selbst wenn Sie DirectoryName Foo sagen Sie es noch Sie Verzeichnispfad WorkDirectory\Foo zurück.</span><span class="sxs-lookup"><span data-stu-id="c18fc-109">This method is case insensitive so even if you say directoryName foo it will still return you directory path WorkDirectory\Foo.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>