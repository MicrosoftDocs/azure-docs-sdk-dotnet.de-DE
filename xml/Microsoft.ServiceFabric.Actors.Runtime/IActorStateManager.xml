<Type Name="IActorStateManager" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager">
  <TypeSignature Language="C#" Value="public interface IActorStateManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorStateManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorStateManager" />
  <TypeSignature Language="F#" Value="type IActorStateManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="33d6f-101">Stellt eine Schnittstelle, die Methoden zum Verwalten der Status der verfügbar macht eine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</span><span class="sxs-lookup"><span data-stu-id="33d6f-101">Represents an interface that exposes methods to manage state of an <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</span></span>
            <span data-ttu-id="33d6f-102">Diese Schnittstelle wird implementiert, indem <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />.</span><span class="sxs-lookup"><span data-stu-id="33d6f-102">This interface is implemented by <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddOrUpdateStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; AddOrUpdateStateAsync&lt;T&gt; (string stateName, T addValue, Func&lt;string,T,T&gt; updateValueFactory, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; AddOrUpdateStateAsync&lt;T&gt;(string stateName, !!T addValue, class System.Func`3&lt;string, !!T, !!T&gt; updateValueFactory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.AddOrUpdateStateAsync``1(System.String,``0,System.Func{System.String,``0,``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateStateAsync : string * 'T * Func&lt;string, 'T, 'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.AddOrUpdateStateAsync (stateName, addValue, updateValueFactory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="addValue" Type="T" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;System.String,T,T&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="33d6f-103">Typ des Werts angegebene Statusname zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="33d6f-103">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="33d6f-104">Der Name des Zustands Akteur hinzufügen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="33d6f-104">Name of the actor state to add or update.</span></span></param>
        <param name="addValue"><span data-ttu-id="33d6f-105">Der Wert des Darstellers Status hinzufügen, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="33d6f-105">Value of the actor state to add if it does not exist.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="33d6f-106">Factory-Funktion zum Generieren der Wert des actorzustands aktualisieren, wenn er vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="33d6f-106">Factory function to generate value of actor state to update if it exists.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-107">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-107">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-108">Fügt einen Akteur Zustand mit der angegebenen Zustand, wenn er noch nicht vorhanden oder mit dem Namen des angegebenen Zustand, wird der Status aktualisiert, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="33d6f-108">Adds an actor state with given state name, if it does not already exist or updates the state with specified state name, if it exists.</span></span> 
            </summary>
        <returns>
            <span data-ttu-id="33d6f-109">Eine Aufgabe, die den asynchronen hinzufügen/aktualisieren Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-109">A task that represents the asynchronous add/update operation.</span></span> <span data-ttu-id="33d6f-110">Der Wert von TResult-Parameter enthält Wert des actorzustands, die hinzugefügt/aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="33d6f-110">The value of TResult parameter contains value of actor state that was added/updated.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="33d6f-111">Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.</span><span class="sxs-lookup"><span data-stu-id="33d6f-111">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="33d6f-112">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-112">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-113">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-113">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.AddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.AddStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="33d6f-114">Typ des Werts angegebene Statusname zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="33d6f-114">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="33d6f-115">Name des Zustands Akteur hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-115">Name of the actor state to add.</span></span></param>
        <param name="value"><span data-ttu-id="33d6f-116">Wert des Darstellers Status hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-116">Value of the actor state to add.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-117">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-117">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-118">Fügt einen Akteur State mit angegebenen Status.</span><span class="sxs-lookup"><span data-stu-id="33d6f-118">Adds an actor state with given state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-119">Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-119">A task that represents the asynchronous add operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="33d6f-120">Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.</span><span class="sxs-lookup"><span data-stu-id="33d6f-120">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="33d6f-121">Ein actorzustands mit Status Name ist bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="33d6f-121">An actor state with given state name already exists.</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="33d6f-122">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-122">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-123">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-123">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ClearCacheAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearCacheAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearCacheAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.ClearCacheAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearCacheAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.ClearCacheAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="33d6f-124">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-124">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-125">Löscht alle zwischengespeicherten Akteur-Status und Vorgänge nachzufolgen <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /> seit der letzten Status beim Speichervorgang.</span><span class="sxs-lookup"><span data-stu-id="33d6f-125">Clears all the cached actor states and any operation(s) performed on <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /> since last state save operation.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-126">Eine Aufgabe, die den asynchronen Cache löschen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-126">A task that represents the asynchronous clear cache operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="33d6f-127">Alle Vorgänge, die für ausgeführt <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /> seit dem letzten Speichern des auf das Löschen des Zwischenspeichers deaktiviert sind, und wird im nächsten Speichervorgang nicht enthalten sein.</span><span class="sxs-lookup"><span data-stu-id="33d6f-127">All the operation(s) performed on <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />  since last save operation are cleared on clearing the cache and will not be included in next save operation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.ContainsStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.ContainsStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName"><span data-ttu-id="33d6f-128">Der Name des Zustands, Akteur.</span><span class="sxs-lookup"><span data-stu-id="33d6f-128">Name of the actor state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-129">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-129">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-130">Überprüft, ob ein actorzustands mit dem angegebenen Namen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="33d6f-130">Checks if an actor state with specified name exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-131">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-131">A task that represents the asynchronous check operation.</span></span> <span data-ttu-id="33d6f-132">Der Wert von TResult-Parameter ist <c>"true"</c> Wenn Status mit dem angegebenen Namen vorhanden andernfalls ist <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="33d6f-132">The value of TResult parameter is <c>true</c> if state with specified name exists otherwise <c>false</c>.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="33d6f-133">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-133">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-134">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-134">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetOrAddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.GetOrAddStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="33d6f-135">Typ des Werts angegebene Statusname zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="33d6f-135">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="33d6f-136">Der Name des Zustands Akteur zum Abrufen oder hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-136">Name of the actor state to get or add.</span></span></param>
        <param name="value"><span data-ttu-id="33d6f-137">Der Wert des Darstellers Status hinzufügen, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="33d6f-137">Value of the actor state to add if it does not exist.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-138">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-138">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-139">Ruft eine actorzustands mit dem Namen angegebenen Status ab, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="33d6f-139">Gets an actor state with the given state name if it exists.</span></span> <span data-ttu-id="33d6f-140">Wenn sie nicht vorhanden ist, erstellt und der Zustand "Neu" mit dem angegebenen Namen und Wert.</span><span class="sxs-lookup"><span data-stu-id="33d6f-140">If it does not exist, creates and new state with the specified name and value.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-141">Eine Aufgabe, die den asynchronen stellt abrufen oder hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-141">A task that represents the asynchronous get or add operation.</span></span> <span data-ttu-id="33d6f-142">Der Wert von TResult-Parameter den Wert des actorzustands mit enthält gegeben Statusname.</span><span class="sxs-lookup"><span data-stu-id="33d6f-142">The value of TResult parameter contains value of actor state with given state name.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="33d6f-143">Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.</span><span class="sxs-lookup"><span data-stu-id="33d6f-143">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="33d6f-144">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-144">The specified state name is null.</span></span>
            <span data-ttu-id="33d6f-145">Geben Sie eine gültigen Status Namenszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="33d6f-145">Provide a valid state name string.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-146">Die Anforderung wurde abgebrochen, unter Verwendung des angegebenen <paramref name="cancellationToken" />.</span><span class="sxs-lookup"><span data-stu-id="33d6f-146">The request was canceled using the specified <paramref name="cancellationToken" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetStateAsync&lt;T&gt; (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetStateAsync&lt;T&gt;(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetStateAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.GetStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="33d6f-147">Typ des Werts angegebene Statusname zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="33d6f-147">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="33d6f-148">Name des abzurufenden Akteur Status.</span><span class="sxs-lookup"><span data-stu-id="33d6f-148">Name of the actor state to get.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-149">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-149">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-150">Ruft ein Akteur Status mit dem angegebenen Namen ab.</span><span class="sxs-lookup"><span data-stu-id="33d6f-150">Gets an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-151">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-151">A task that represents the asynchronous get operation.</span></span> <span data-ttu-id="33d6f-152">Der Wert von TResult-Parameter den Wert des actorzustands mit enthält gegeben Statusname.</span><span class="sxs-lookup"><span data-stu-id="33d6f-152">The value of TResult parameter contains value of actor state with given state name.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="33d6f-153">Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.</span><span class="sxs-lookup"><span data-stu-id="33d6f-153">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">
            <span data-ttu-id="33d6f-154">Ein actorzustands mit Status Name ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="33d6f-154">An actor state with given state name does not exist.</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="33d6f-155">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-155">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-156">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-156">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetStateNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; GetStateNamesAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; GetStateNamesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetStateNamesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStateNamesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iActorStateManager.GetStateNamesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="33d6f-157">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-157">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-158">Erstellt ein aufzählbares Objekt von allen Akteur Ländernamen für aktuelle Akteur.</span><span class="sxs-lookup"><span data-stu-id="33d6f-158">Creates an enumerable of all actor state names for current actor.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-159">Eine Aufgabe, die den asynchronen Enumerationsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-159">A task that represents the asynchronous enumeration operation.</span></span> <span data-ttu-id="33d6f-160">Der Wert von TResult-Parameter ist ein aufzählbares Objekt von allen Akteur Ländernamen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-160">The value of TResult parameter is an enumerable of all actor state names.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-161">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-161">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.RemoveStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.RemoveStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName"><span data-ttu-id="33d6f-162">Name des Zustands Akteur zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-162">Name of the actor state to remove.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-163">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-163">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-164">Entfernt ein actorzustands mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-164">Removes an actor state with specified state name.</span></span>
            </summary>
        <returns><span data-ttu-id="33d6f-165">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-165">A task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">
            <span data-ttu-id="33d6f-166">Ein actorzustands mit Status Name ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="33d6f-166">An actor state with given state name does not exist.</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="33d6f-167">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-167">The specified state name is null.</span></span> </exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-168">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-168">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SaveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveStateAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveStateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveStateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.SaveStateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="33d6f-169">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-169">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-170">Speichert alle zwischengespeicherten statusänderungen (Hinzufügen/Aktualisieren/Entfernen), die seit dem letzten Aufruf von <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" /> von Akteur Runtime oder vom Benutzer explizit.</span><span class="sxs-lookup"><span data-stu-id="33d6f-170">Saves all the cached state changes (add/update/remove) that were made since last call to <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" /> by actor runtime or by user explicitly.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-171">Eine Aufgabe, die den asynchronen Speichervorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-171">A task that represents the asynchronous save operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SetStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.SetStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="33d6f-172">Typ des Werts angegebene Statusname zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="33d6f-172">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="33d6f-173">Name des Zustands Akteur festlegen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-173">Name of the actor state to set.</span></span></param>
        <param name="value"><span data-ttu-id="33d6f-174">Der Wert des Darstellers Status.</span><span class="sxs-lookup"><span data-stu-id="33d6f-174">Value of the actor state.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-175">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-175">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-176">Legt ein Akteur Zuständen mit angegebenen Statusname angegebenen Wert.</span><span class="sxs-lookup"><span data-stu-id="33d6f-176">Sets an actor state with given state name to specified value.</span></span>
            <span data-ttu-id="33d6f-177">Wenn ein Akteur Status mit dem angegebenen Namen nicht vorhanden ist, wird er hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-177">If an actor state with specified name does not exist, it is added.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-178">Eine Aufgabe, die asynchrone Operation darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-178">A task that represents the asynchronous set operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="33d6f-179">Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.</span><span class="sxs-lookup"><span data-stu-id="33d6f-179">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="33d6f-180">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-180">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-181">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-181">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryAddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryAddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.TryAddStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="33d6f-182">Typ des Werts angegebene Statusname zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="33d6f-182">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="33d6f-183">Name des Zustands Akteur hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-183">Name of the actor state to add.</span></span></param>
        <param name="value"><span data-ttu-id="33d6f-184">Wert des Darstellers Status hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-184">Value of the actor state to add.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-185">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-185">The token to monitor for cancellation requests.</span></span>
            <span data-ttu-id="33d6f-186">Dies ist optional und wird standardmäßig auf<see cref="P:System.Threading.CancellationToken.None" /></span><span class="sxs-lookup"><span data-stu-id="33d6f-186">This is optional and defaults to <see cref="P:System.Threading.CancellationToken.None" /></span></span></param>
        <summary>
            <span data-ttu-id="33d6f-187">Versuche, einen Akteur hinzuzufügen Zuständen mit angegebenen Statusname und Wert.</span><span class="sxs-lookup"><span data-stu-id="33d6f-187">Attempts to add an actor state with given state name and value.</span></span> <span data-ttu-id="33d6f-188">Gibt "false" werden, wenn ein Akteur Status mit dem gleichen Namen ist bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="33d6f-188">Returns false if an actor state with the same name already exists.</span></span> 
            </summary>
        <returns>
            <span data-ttu-id="33d6f-189">Das Hinzufügen einer booleschen Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-189">A boolean task that represents the asynchronous add operation.</span></span> <span data-ttu-id="33d6f-190">Gibt "true" Wenn der Wert erfolgreich hinzugefügt und "false", wenn ein Akteur Status mit dem gleichen Namen bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="33d6f-190">Returns true if the value was successfully added and false if an actor state with the same name already exists.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="33d6f-191">Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.</span><span class="sxs-lookup"><span data-stu-id="33d6f-191">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="33d6f-192">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-192">The specified state name is null.</span></span>
            <span data-ttu-id="33d6f-193">Geben Sie eine gültigen Status Namenszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="33d6f-193">Provide a valid state name string.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-194">Die Anforderung wurde abgebrochen, unter Verwendung des angegebenen <paramref name="cancellationToken" />.</span><span class="sxs-lookup"><span data-stu-id="33d6f-194">The request was canceled using the specified <paramref name="cancellationToken" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetStateAsync&lt;T&gt; (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetStateAsync&lt;T&gt;(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryGetStateAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iActorStateManager.TryGetStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="33d6f-195">Typ des Werts angegebene Statusname zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="33d6f-195">Type of value associated with given state name.</span></span></typeparam>
        <param name="stateName"><span data-ttu-id="33d6f-196">Name des abzurufenden Akteur Status.</span><span class="sxs-lookup"><span data-stu-id="33d6f-196">Name of the actor state to get.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-197">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-197">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-198">Versucht, eine actorzustands mit dem angegebenen Namen abzurufen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-198">Attempts to get an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-199">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-199">A task that represents the asynchronous get operation.</span></span> <span data-ttu-id="33d6f-200">Der Wert von TResult-Parameter enthält <see cref="T:Microsoft.ServiceFabric.Data.ConditionalValue`1" /> , der angibt, ob die actorzustands vorhanden ist und der Wert des actorzustands vorhanden.</span><span class="sxs-lookup"><span data-stu-id="33d6f-200">The value of TResult parameter contains <see cref="T:Microsoft.ServiceFabric.Data.ConditionalValue`1" /> indicating whether the actor state is present and the value of actor state if it is present.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="33d6f-201">Der Typ der Statuswert <typeparamref name="T" /> muss <see href="https://msdn.microsoft.com/library/ms731923.aspx">Datenvertrag</see> serialisierbar.</span><span class="sxs-lookup"><span data-stu-id="33d6f-201">The type of state value <typeparamref name="T" /> must be <see href="https://msdn.microsoft.com/library/ms731923.aspx">Data Contract</see> serializable.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="33d6f-202">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-202">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-203">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-203">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TryRemoveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryRemoveStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryRemoveStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryRemoveStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.TryRemoveStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName"><span data-ttu-id="33d6f-204">Name des Zustands Akteur zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-204">Name of the actor state to remove.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="33d6f-205">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-205">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="33d6f-206">Versucht, eine actorzustands mit dem angegebenen Namen zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-206">Attempts to remove an actor state with specified state name.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33d6f-207">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="33d6f-207">A task that represents the asynchronous remove operation.</span></span> <span data-ttu-id="33d6f-208">Der Wert von TResult-Parameter gibt an, ob der Zustand erfolgreich entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="33d6f-208">The value of TResult parameter indicates if the state was successfully removed.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="33d6f-209">Der Name des angegebenen Zustand ist null.</span><span class="sxs-lookup"><span data-stu-id="33d6f-209">The specified state name is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="33d6f-210">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="33d6f-210">The operation was canceled.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>