<Type Name="ServicePackageActivationMode" FullName="System.Fabric.Description.ServicePackageActivationMode">
  <TypeSignature Language="C#" Value="public enum ServicePackageActivationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServicePackageActivationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePackageActivationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServicePackageActivationMode" />
  <TypeSignature Language="F#" Value="type ServicePackageActivationMode = " />
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
            Beschreibt Dienstmodus Paket Aktivierung für einen Service Fabric-Dienst an. Dadurch wird angegeben, die zum Zeitpunkt der Erstellung des Diensts (mit <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription)" />) oder Dienstgruppe (mit <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />) über <see cref="P:System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />.
            </para>
      <para>
            Wenn beim Erstellen des Diensts oder einer Dienstgruppe wurde kein Wert angegeben, wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> Modus.
            </para>
    </summary>
    <remarks>
      <para>
            Betrachten Sie ein Beispiel, in dem Sie haben einen Anwendungstyp für "AppTypeA" das ServicePackage "ServicePackageA" registriert "ServiceTypeA" enthält und Sie viele Dienste von "ServiceTypeA" erstellen. Sagen "Fabric: / App1_of_AppTypeA/Serv_1" auf "Fabric: / App1_of_AppTypeA/Serv_N" mit ServicePackageActivation Modus <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> und "Fabric: / App1_of_AppTypeA/Serv_11", "Fabric: / App1_of_AppTypeA/Serv_NN" mit ServicePackageActivation-Modus <see cref="F:System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />.
            </para>
      <para>
            Auf einem bestimmten Knoten, Replikat (oder Instanz) des Diensts "Fabric: / App1_of_AppTypeA/Serv_1", "Fabric: / App1_of_AppTypeA/Serv_N" wird platziert werden die gleichen Aktivierung "ServicePackageA", deren <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> wird immer eine leere Zeichenfolge sein. Allerdings Replikat (oder Instanz) der einzelnen "Fabric: / App1_of_AppTypeA/Serv_11", "Fabric: / App1_of_AppTypeA/Serv_NN" eingefügt wird in einen eigenen dedizierten Aktivierung von "ServicePackageA", und jede dieser Aktivierung wird eine eindeutige nicht leere Zeichenfolge als haben<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />.
            </para>
      <para>
            Nachdem Sie den Dienst erstellt haben, erhalten Sie <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> der aktivierten ServicePackage(s) auf einen Knoten durch Abfragen <see cref="T:System.Fabric.Query.DeployedServicePackageList" /> auf diesem Knoten mithilfe <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />.
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ExclusiveProcess">
      <MemberSignature Language="C#" Value="ExclusiveProcess" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePackageActivationMode ExclusiveProcess = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />
      <MemberSignature Language="VB.NET" Value="ExclusiveProcess" />
      <MemberSignature Language="F#" Value="ExclusiveProcess = 1" Usage="System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            Mit dieser Aktivierung müssen Modus, jedes Replikat oder eine Instanz des Diensts auf einem bestimmten Knoten eine eigenen dedizierte Aktivierung des Dienstpakets auf einem Knoten.
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="SharedProcess">
      <MemberSignature Language="C#" Value="SharedProcess" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePackageActivationMode SharedProcess = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />
      <MemberSignature Language="VB.NET" Value="SharedProcess" />
      <MemberSignature Language="F#" Value="SharedProcess = 0" Usage="System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>
            Dies ist der Standardmodus für die Aktivierung. Für diese Aktivierung werden Modus, Replikate oder Instanzen aus anderen Partitionen der Dienst auf einem bestimmten Knoten denselben Aktivierung des Dienstpakets auf einem Knoten freigeben.
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>